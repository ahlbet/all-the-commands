### Git

git branch | grep ‘your_string_here’
git branch | grep ‘your_string_here’ | xargs git branch -d

#### Git - Heroku

git push heroku development:master

### React Native

adb -s <device name> reverse tcp:8081 tcp:8081
cd android && ./gradlew assembleRelease

### Rails

foreman start -f Procfile.dev
rails db:drop db:create db:migrate db:seed
