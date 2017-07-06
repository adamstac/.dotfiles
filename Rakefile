require "fileutils"
require "rake"

desc "Symlink .sublime/Preferences.sublime-settings to Packages/User/Preferences.sublime-settings"
task :link_sublime do
  dot_sublime_preferences = File.expand_path("~/.sublime/Preferences.sublime-settings")
  user_preferences = File.expand_path("~/Library/Application Support/Sublime Text 3/Packages/User/Preferences.sublime-settings")

  FileUtils.ln_s(dot_sublime_preferences, user_preferences)
end
