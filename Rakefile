
task :build do
  Dir.glob('fortunes/*').reject { |f| f =~ /\.dat$/ }.each do |f|
    system("strfile #{f}")
  end
end

task :default => :build

