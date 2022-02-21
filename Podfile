# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

def shared_pods
  use_frameworks!
  inhibit_all_warnings!
  
  pod 'SwiftyJSON', '5.0.0'
  
end


target 'TestApp' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for TestApp
  shared_pods

  target 'TestAppTests' do
    inherit! :search_paths
    # Pods for testing
    shared_pods
  end

  target 'TestAppUITests' do
    # Pods for testing
    shared_pods
  end

end
