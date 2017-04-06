# Uncomment the next line to define a global platform for your project
platform :ios, '10.2'
# Comment the next line if you're not using Swift and don't want to use dynamic frameworks
def shared_pods
use_frameworks!
   pod 'Alamofire', '~> 4.4'
   pod 'SwiftyJSON'
end
target 'Modes' do
   # Pods for Modes
   shared_pods
end
target 'ModesTests' do
   inherit! :search_paths
   # Pods for testing
   shared_pods

 end

 target 'ModesUITests' do
   inherit! :search_paths
    # Pods for testing
    shared_pods

   end
