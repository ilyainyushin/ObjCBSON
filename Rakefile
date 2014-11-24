task :install do
  raise unless system "sudo -k gem install xcpretty"
end

task :test do
  raise unless system "bash -c 'set -o pipefail && xcodebuild test -workspace Example/ObjCBSON-experimental.xcworkspace -scheme ObjCBSON-experimental -sdk iphonesimulator ONLY_ACTIVE_ARCH=NO | xcpretty -c'"
end

task :clean do
  raise unless system "xcodebuild clean -workspace Example/ObjCBSON-experimental.xcworkspace -scheme ObjCBSON-experimental"
end
