require 'html-proofer'

task :default => [:build]

task :clean do
	sh 'rm -rf ./_site'
end

task :build do
	system("jekyll build")
end

task :rebuild => [:clean, :build] do

end

task :test do
  HTMLProofer.check_directory("./_site", {
    :allow_hash_href => true,
    :disable_external => true,
		:assume_extension => true
    }).run
end

task :cibuild => [:rebuild, :test] do

end
