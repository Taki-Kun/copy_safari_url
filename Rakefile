desc "Install the workflow to your services folder, under Applications/Safari"
task :install do
  puts "Copying copy_safari_url.workflow to your services folder"
  output = "~/Library/Services"
  system "mkdir -p #{output}"
  system "cp -r *.workflow #{output}"
  puts "Done"
end