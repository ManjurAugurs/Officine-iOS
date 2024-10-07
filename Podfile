# Uncomment the next line to define a global platform for your project
#platform :ios, '15.0'

# ignore all warnings from all pods
inhibit_all_warnings!

target 'OfficineTop' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!
  
  # Pods for OfficineTop
  pod 'IQKeyboardManagerSwift'
  pod 'JGProgressHUD'
  pod 'Alamofire'
  pod 'AlamofireImage', '~> 4.1'
  pod 'SwiftLint'
  pod 'DropDown', '~> 2.3.13'
  pod 'ImageSlideshow'
  pod 'ImageSlideshow/Alamofire'
  pod 'Cosmos', '~> 19.0', :inhibit_warnings => true
  pod 'CropViewController'
  pod 'AlignedCollectionViewFlowLayout'
  
  pod 'FSCalendar'
  pod 'GoogleMaps'
  pod 'GooglePlaces'
  pod 'GooglePlacesSearchController'
  
  pod 'FirebaseCore'
  pod 'FirebaseMessaging'
  pod 'FirebaseAnalytics'
  pod 'FirebaseCrashlytics'
  
  pod 'SwiftKeychainWrapper'
  pod 'SDWebImage'
  pod 'ReadMoreTextView'
  pod 'MultiSlider'
  pod 'KSNumericTextField'
  pod 'YiAppUpdater'
  pod 'YouTubePlayer'
  pod 'RSKPlaceholderTextView'
  
  #  # For Branch iOS SDK 2.0.0+
  pod 'BranchSDK'
  
  
  
  
  pod 'FBSDKCoreKit'
  pod 'FBSDKLoginKit'
  pod 'FBSDKShareKit'
      
#  pod 'PayPal/PayPalWebPayments'
  
end

post_install do |installer|
  installer.generated_projects.each do |project|
    project.targets.each do |target|
      target.build_configurations.each do |config|
        config.build_settings['IPHONEOS_DEPLOYMENT_TARGET'] = '16.0'
      end
    end
  end
end

