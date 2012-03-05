require 'albacore'

desc "create the nuget package"
nuspec create_ironruby_nuspec do |nuspec|
   nuspec.id = 'IronRuby'
   nuspec.version = '1.1.4'
   nuspec.authors = 'IronRuby Community'
   nuspec.owners = 'IronRuby Community'
   nuspec.description = "the Ruby programming language for the .NET Framework"
   nuspec.licenseUrl = "http://ironruby.codeplex.com/license"
   nuspec.projectUrl = "http://ironruby.codeplex.com/"
   nuspec.tags "ironruby ruby"
   nuspec.working_directory = "bin/pkg"
   nuspec.output_file = "IronRuby.nuspec"
   nuspec.file "../tools/*.exe", "tools"
   nuspec.file "..", 'lib/net40'
   nuspec.file "", 'lib/sl3-wp'
   nuspec.file "", 'lib/sl4'
   nuspec.framework_assembly "System.CoreEx", "net40"
   nuspec.framework_assembly "System.Reactive", "net40"
end


