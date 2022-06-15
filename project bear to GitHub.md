project bear to GitHub

---
코드예제
```python
md_text = md_text.replace('\n* ', '\n- ')
md_text = md_text.replace('\n    * ', '\n\t- ')
md_text = md_text.replace('\n        * ', '\n\t\t- ')
```

크론탭 추가
```Bash
cat <(crontab -l) <(echo "1 5 * * * /root/myscript.sh") | crontab -

주석처리
crontab -l | sed -e 's/\(.*명령어\)/#\1/' | crontab

```


파이선 os.walk
./.bash_logout
./amrood.tar.gz
./.emacs
./httpd.conf
이런 목록을 얻을 수 있음.

<!-- {BearID:777F8ABF-A492-494F-81D2-E597DD68261D-67965-000005AB90B45421} -->
