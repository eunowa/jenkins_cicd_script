# jenkins_cicd_script

Playbook 작성

vi first-playbook.yml
- https://github.com/joneconsulting/jenkins_cicd_script/blob/master/playbook_script/playbook-sample0.yml
vi playbook-sample1.yml
- https://github.com/joneconsulting/jenkins_cicd_script/blob/master/playbook_script/playbook-sample1.yml
MacOS) vi playbook-sample2.yml
- https://github.com/joneconsulting/jenkins_cicd_script/blob/master/playbook_script/playbook-sample2.yml
Windows) vi playbook-sample2-windows.yml
- https://github.com/joneconsulting/jenkins_cicd_script/blob/master/playbook_script/playbook-sample2-windows.yml
Linux) vi playbook-sample2-linux.yml
- https://github.com/joneconsulting/jenkins_cicd_script/blob/master/playbook_script/playbook-sample2-linux.yml
 

tomcat을 다운로드 받는 부분에서 checksum 처리 시 아래와 같은 오류가 발생한 경우, OS 환경에 맞는 샘플 파일로 변경해서 실행해 보시기 바랍니다. 

Windows 환경에서의 Playbook 실행 시 아래 파일을 사용해 주세요. 
- https://github.com/joneconsulting/jenkins_cicd_script/blob/master/playbook_script/playbook-sample2-windows.yml
Ansible-server에서 다음 명령어 ca-certificates 모듈 업데이트 필요
- yum install -y ca-certitificates
Linux 환경에서의 Playbook 실행 시 아래 파일을 사용해 주세요. 
- https://github.com/joneconsulting/jenkins_cicd_script/blob/master/playbook_script/playbook-sample2-linux.yml
