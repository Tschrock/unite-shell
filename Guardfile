guard :copy, from: 'src/assets', to: 'dist/unite@hardpixel.eu/assets', mkpath: true, run_at_start: true
guard :copy, from: 'src/meta', to: 'dist/unite@hardpixel.eu', mkpath: true, run_at_start: true

guard 'sprockets', destination: 'dist/unite@hardpixel.eu', asset_paths: ['src/sass'] do
  watch (%r{src/sass/*}) { 'dist/unite@hardpixel.eu/stylesheet.css' }
end

guard 'sprockets', destination: 'dist/unite@hardpixel.eu', asset_paths: ['src/js'] do
  watch (%r{src/js/*}) { 'dist/unite@hardpixel.eu/extension.js' }
end