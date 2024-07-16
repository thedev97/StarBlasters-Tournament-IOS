# platform :ios, '9.0'

target 'StarWarsBlastersTournament' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for StarWarsBlastersTournament
  pod 'Alamofire',  '~> 5.9.1'
  pod 'SwiftyJSON', '~> 4.0'

  # Pods for StarWarsBlastersTournament
end

post_install do |installer|
    installer.generated_projects.each do |project|
          project.targets.each do |target|
              target.build_configurations.each do |config|
                  config.build_settings['IPHONEOS_DEPLOYMENT_TARGET'] = '13.0'
               end
          end
   end
end
