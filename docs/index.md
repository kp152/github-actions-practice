# GitHub Actions 缁冧範椤圭洰

娆㈣繋鏉ュ埌鏈」鐩殑鏂囨。绔欑偣锛?
鏈」鐩槸寮€婧愯蒋浠惰璁′笌鍒嗘瀽璇剧▼鐨勫疄楠屼簩锛屼富瑕佸唴瀹规槸锛?
- 浣跨敤 **GitHub Actions** 瀹炵幇 Python 椤圭洰鐨勮嚜鍔ㄦ祴璇?- 浣跨敤 **MkDocs** 鎼缓鏂囨。绔欑偣
- 閫氳繃 **GitHub Pages** 鑷姩閮ㄧ讲鏂囨。缃戠珯

## 椤圭洰缁撴瀯

    github-actions-practice/
    鈹溾攢鈹€ calculator.py              # 璁＄畻鍣ㄦā鍧?    鈹溾攢鈹€ test_calculator.py         # pytest 娴嬭瘯鏂囦欢
    鈹溾攢鈹€ mkdocs.yml                 # MkDocs 閰嶇疆
    鈹溾攢鈹€ docs/                      # 鏂囨。婧愮爜鐩綍
    鈹?  鈹溾攢鈹€ index.md
    鈹?  鈹溾攢鈹€ about.md
    鈹?  鈹溾攢鈹€ guide.md
    鈹?  鈹斺攢鈹€ api.md
    鈹斺攢鈹€ .github/workflows/
        鈹溾攢鈹€ ci.yml                 # CI 娴嬭瘯宸ヤ綔娴?        鈹斺攢鈹€ deploy.yml             # Pages 閮ㄧ讲宸ヤ綔娴?
## 蹇€熷紑濮?
鍏嬮殕浠撳簱鍚庯紝鏈湴杩愯娴嬭瘯锛?
    git clone https://github.com/KP152/github-actions-practice.git
    cd github-actions-practice
    pip install pytest
    pytest -v