desc "Print a nice greeting"
task :greet do
  puts "What's your name?"
  name = STDIN.gets
  puts "Hello, " + name
end

desc "Tell the time"
task :time do
 puts Time.new
end

desc "Prints favorite food"
task :food do
  ENV["FAVORITE_FOOD"]
  puts "Your favorite food is #{ENV["FAVORITE_FOOD"]}"
end

