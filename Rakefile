task :build do
	system('mkdir -p build; ls *.rb | grep -v jekyll_indextank.rb | while read file; do cat $file; echo ""; done > build/jekyll_indextank.rb')
end