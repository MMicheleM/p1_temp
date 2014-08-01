p1_temp
=======

FOR RAKE FILE

desc "populate the test database with sample data"
task "db:populate" do
  StudentsImporter.import
end
