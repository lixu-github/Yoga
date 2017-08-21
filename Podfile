# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'Yoga' do
  # Uncomment the next line if you're using Swift or would like to use dynamic frameworks
  # use_frameworks!

  # Pods for Yoga

  target 'YogaTests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'YogaUITests' do
    inherit! :search_paths
    # Pods for testing
  end

pod 'React', :path => './RNComponents/node_modules/react-native', :subspecs => [
    'Core',
    'DevSupport', # Include this to enable In-App Devmenu if RN >= 0.43
    'RCTText',
    'RCTNetwork',
    'RCTWebSocket', # needed for debugging
    # Add any other subspecs you want to use in your project
  ]
  # Explicitly include Yoga if you are using RN >= 0.42.0
  pod "Yoga", :path => "./RNComponents/node_modules/react-native/ReactCommon/yoga"

end
