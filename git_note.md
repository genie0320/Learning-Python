# github 사용법

## git fetch & git merge origin/master

git 사용시, staging이라는 과정을 거치는데 이는 일종의 '대기소/검역소'이다. commit을 해줘야 최종적으로 코드베이스에 '반영'이 된다. 

`git fetch origin`는 원격코드베이스의 변경사항을 가져오지만, 로컬코드베이스에 반영하지는 않는다. (이때 변경사항은 일종의 '검역소'에 머물게 된다. 따라서 변경사항을 검토하는 기능도 있을 듯 한다. )

`git merge origin/master(maain)`로 가져온 변경사항을 로컬코드베이스에 반영하는 것.

