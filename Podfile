platform :ios, '10.0'

use_frameworks!
inhibit_all_warnings!

def main_pods

  pod 'AlamofireImage', '4.2.0'
  pod 'lottie-ios', '3.2.3'
  pod 'PromiseKit', '6.17.1'
  pod 'PromiseKit/CoreLocation', '6.17.1'
  pod 'Reusable', '4.1.1'
  pod 'SkeletonView', '1.29.2'
  pod 'SnapKit', '5.0.1'
  pod 'SwiftLint', '0.43.1'
end

def restapi_pods
  pod 'Alamofire', '5.4.3'
  #pod 'Moya'
end

def tests_pods
  pod 'Nimble', '9.2.0'
  pod 'Nimble-Snapshots', '9.1.0'
  pod 'Quick', '4.0.0'
end

target 'moviesvip' do
  main_pods
  restapi_pods

  target 'moviesvipTests' do
    inherit! :search_paths
    tests_pods
  end

  target 'moviesvipUITests' do
    tests_pods
  end

end
