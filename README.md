このコードは最大10件の画像検索が出来るAPIです。
使う際は、imagesディレクトリとmainファイルを作成してください。

以下がmainファイルに書くコードです。
"""main.py"""

from API.search import image

def main():
    titel = image("姫路城") # ここに検索したい画像のタイトルを入れる
    image.get_image(titel)

if __name__ == "__main__":
    main()

"""-------"""