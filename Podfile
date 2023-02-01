source 'https://github.com/CocoaPods/Specs.git'
workspace 'Test'
platform :ios, '10.0'
inhibit_all_warnings!
use_frameworks!

project 'This is a test', 'Test' => :release, 'Stage' => :release

target 'Carrier Dashboard' do
	project 'PodTest'
    
    # Swift 4
    pod 'ReachabilitySwift', '~> 4.1.0'
    pod 'JWTDecode', '2.1.1'
    pod 'TQLUtils', '~> 3.0.0'
    pod 'SwiftKeychainWrapper', '~> 3.0'
    pod 'AppAuth', '~> 0.9.1'
    pod 'AppCenter'
    pod 'AppCenter/Distribute'
    #pod 'Wormholy', '1.0', :configurations => ['Stage', 'Debug']
    pod 'SwiftLint', :configurations => ['Stage', 'Debug']
    
    # Objective-C
    pod 'GoogleAnalytics'
    pod 'Firebase/Core'
    pod 'Firebase/DynamicLinks'
    pod 'Firebase/Messaging'
    pod 'Firebase/Performance'
    pod 'Fabric'
    pod 'Crashlytics'
    pod 'Wit', '~> 4.1.0'
    pod 'MMDrawerController', '~> 0.6.0'
    pod 'MBProgressHUD', '~> 0.9.2'
    pod 'M13Checkbox'
    pod 'HMSegmentedControl'

    # C++
    pod 'OpenCV', '3.1.0.1'

    target 'PodTest' do
        inherit! :search_paths
        # Pods for testing
    end
end
