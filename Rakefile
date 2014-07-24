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

task :wake_up do
  puts "Wake Up!"
end

task :get_dressed => :wake_up do
  puts "Get dressed!"
end

task :eat_breakfast do
  puts "Eat breakfast!"
end

task :brush_teeth do
  puts "Brush your teeth"
end

task :ready_for_class => [:wake_up, :eat_breakfast, :brush_teeth] do
  puts "Ready for class!"
end