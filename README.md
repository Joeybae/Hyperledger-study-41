# Hyperledger-study-41

하이퍼레져 앱 만들기 실습 41일차 - chaincode 내용 변경 후 반영

1. fabcar.go 수정

        # cd fabric-samples/chaincode/fabcar/go
        # 수정 후 저장

2. teardown 실행

        # cd fabric-samples/basic-network/
        # ./teardown.sh

3. chaincode docker images 삭제

        # cd fabric-samples/fabcar
        # docker rm -f $(docker ps -aq)
        # docker network prune
        # y

4. Fabric 시작

        # ./startFabric.sh

5. 체인코드 호출

        # node query.js

6. 변경 한 내용 확인
