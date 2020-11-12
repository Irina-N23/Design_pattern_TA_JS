# Design_pattern_TA_JS
[Framework] - Design patterns in Automated testing / EPMFARMATS-12779


## CL command for running tests via Chrome browser:

#### _evernote:_
npm run test -- --suite=evernote --params.login.email "sometestuserqa@gmail.com" --params.login.password "everNote#28Qzx"

#### _angularjs:_
npm run test -- --suite=angularjs

#### _all (1 instance):_
npm run test -- --suite=all --params.login.email "sometestuserqa@gmail.com" --params.login.password "everNote#28Qzx"
_-or-_
npm run test -- --params.login.email "sometestuserqa@gmail.com" --params.login.password "everNote#28Qzx"

#### _all (2 instances):_
npm run test -- --suite=all --instances=2 --params.login.email "sometestuserqa@gmail.com" --params.login.password "everNote#28Qzx"
_- or -_
npm run test -- --instances=2 --params.login.email "sometestuserqa@gmail.com" --params.login.password "everNote#28Qzx"


## An example of command for running a test via Firefox browser:**

#### _angularjs:_
npm run test -- --suite=angularjs --browser=firefox