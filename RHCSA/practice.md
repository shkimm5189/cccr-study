# 장치 5G 2개 를 추가하세여
# 0. 추가한 첫번째 장치를 myvg로 설정하고 testlv에 2.5G할당하세요
# 1. root의 비밀번호를 root로 설정하세요
# 2. hostname을 본인이름으로 설정하세요
# 3. grp 볼륨 그룹을 만들고 lv1을 만들어 /mnt/share에 영구마운트 하세요 단, PE사이즈 8mb, ext4로 포멧하세요

# 4. 512mb의 스왑 파티션을 만들고 영구마운트 하세요.
# 5. manager 그룹을 만드시오
- 보조그룹이 manager인 harry유저를 만드시오
- sara계정도 보조그룹이 manager 입니다
- manager 권한이 없는 sarah 계정을 만드시오 sarah는 로그인이 불가능하여야 합니다
- 모든 계정의 패스워드는 test여야 합니다
# 7./etc/fstab 파일을 /var/tmp/fstab 으로 복사 한후 권한 설정을 하시오
- harry 유저와 sarah 유저는 해당 파일을 읽고 쓸수 있고
- sarah 유저는 아무런 권한도 없어야 합니다
- 현재 또는 미래의 모든 유저들은 읽기 권한이 있어야합니다
# 8. testlv에 700M를 추가하세요
# 8. harry 유저가 매일 5분마다 수행하는 echo test 반복작업을 등록하시오
# 9. server.example.com 으로 시간을 동기화하는 클라이언트 설정을 하시오
# 10. /USR 폴더의 내용을 /root/usr.tar.bzip2 아카이브로 생성하시오, 단 bzip으로 압축되어야 합니다

# 11.  /share 디렉토리를 client의 주소로만 공유하고 /mnt/share에 영구 마운트하세요

# 12. server에서 /mydir 밑에 docs,pdf,test를 모든 사용자에게 읽기 권한으로만 설정하고 client에서 자동 마운트 방식으로 /mydir 마운트하세요 (docs,pdf,test)
