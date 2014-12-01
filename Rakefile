task default: %w[clean build show]

task :clean do
    `rm -rf presentation/slides`
end

task :build do
    `slideshow build presentation/presentation.md -o presentation/slides -t reveal`
    `cp presentation/presentation.css presentation/slides/`
    `cp -r presentation/images presentation/slides/`
end

task :show do
    `open presentation/slides/presentation.html`
end

task :pdf do
  `wkhtmltopdf --outline --orientation Landscape presentation/slides/presentation.html presentation/slides/presentation.pdf`
end


