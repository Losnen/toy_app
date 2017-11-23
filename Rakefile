# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.

require_relative 'config/application'

desc "db:migrate"
task :dbmigrate do
  exec 'rails db:migrate'
end

Rails.application.load_tasks
