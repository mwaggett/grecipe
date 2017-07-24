LIBDIR = File.expand_path(File.join(File.dirname(__FILE__), 'lib'))
$:.unshift(LIBDIR)

tasks_directory = File.expand_path(File.join(File.dirname(__FILE__), 'tasks'))

# Automatically load any rake files in the tasks directory
Dir.glob("#{tasks_directory}/*.rake").each { |task|
  load task
}
