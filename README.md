# html2pdf


fetch news:

'wget --limit-rate=200k --no-clobber --convert-links --random-wait -r -p -E -e robots=off -U mozilla  "http://news.sciencenet.cn/dz/dzzz_1.aspx?dzsbqkid=24833"'

usage:

'libreoffice --headless --convert-to pdf ./template.html'