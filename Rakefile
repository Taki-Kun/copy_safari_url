desc "Install the workflow to your services folder, under Applications/Safari"
task :install => :compile do
  puts "Copying copy_safari_url.scpt to your scripts folder"
  output = "~/Library/Services"
  system "mkdir -p #{output}"
  system "cp -r *.workflow #{output}"
  puts "Done"
end