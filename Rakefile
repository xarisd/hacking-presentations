task default: %w[clean build]

task :clean do
    `rm -rf presentation/slides`
end

task :build do
    `slideshow build presentation/presentation.md -o presentation/slides -t reveal`
    `cp presentation/presentation.css presentation/slides/`
    `cp -r presentation/images presentation/slides/`
end
