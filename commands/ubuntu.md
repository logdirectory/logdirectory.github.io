# Ubuntu Command 정리

## apt-get 
> 설치위치 `/var/cache/apt/archive/`
- 모든 패키지 업그레이드 `sudo apt-get upgrade`
- 패키지 인덱스 정보 업데이트(/etc/apt/sources.list) `sudo apt-get update`
- 패키지 설치 `sudo apt-get install 패키지이름`
- 패키지 재설치 `apt-get --reinstall install 패키지이름`
- 패키지 삭제(설정파일 **유지**) `sudo apt-get remove 패키지이름`
- 패키지 삭제(설정파일 **삭제**) `sudo apt-get --purge remove 패키지이름`
- 패키지 검색 `sudo apt-cache  search 패키지이름`
- 패키지 정보 보기 `sudo apt-cache show 패키지이름`
