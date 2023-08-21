Variables
The last step is to make sure you set up the project-level variables we used throughout the configuration above:

google_play_service_account_api_key_json: see https://docs.fastlane.tools/getting-started/android/setup/#collect-your-google-credentials
oauth_client_id
oauth_client_id, protected, production environment
oauth_client_secret
oauth_client_secret, protected, production environment
oauth_redirect_uri
oauth_redirect_uri, protected, production environment
signing_jks_file_hex: xxd -p gitter-android-app.jks
signing_key_alias
signing_key_password
signing_keystore_password
If you are using the same create-changlog-mr.sh script as us,

deploy_key_android_repo: see https://docs.gitlab.com/ee/user/project/deploy_tokens/
gitlab_api_access_token: see https://docs.gitlab.com/ee/user/profile/personal_access_tokens.html (we use a bot user)