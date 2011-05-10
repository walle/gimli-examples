# A sample Guardfile
# More info at https://github.com/guard/guard#readme

guard 'gimli', :outputdir => 'build' do
  watch(%r{.+\.(md|mkdn?|mdown|markdown|textile|creole|(media)?wiki)})
end

guard 'gimli', :outputdir => 'build', :stylesheet => 'table.css' do
  watch(%r{.+\.(org)})
end

