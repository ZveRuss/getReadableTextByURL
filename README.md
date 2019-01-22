test_task_Tenzor

Module for processing the text of the article by URL, based on Requests and BeautifulSoup4 libraries.
Contain class MiniReadability with next methods:

- get_text(self) - return clear text of article
- write_in_file(self, text) - # Write file in path, stored in self.path:
"[CUR_DIR]/host/path_item1/path_item2/..." with filename, stored in
MiniReadability.filename. Saves to utf-8.

Example for using: "python readable.py https://lenta.ru/news/2019/01/22/brain/"


Tested on articles:
- https://www.e1.ru/news/spool/news_id-65858581.html - test passed successfully
- https://lenta.ru/news/2019/01/22/brain/ - test passed succesfully
- https://lenta.ru/news/2019/01/22/platskart/ - test passed succesfully
- https://lenta.ru/news/2019/01/21/whatsup_whatsapp - test passed succesfully


Further development plans:
- creating a settings file with site processing templates for more accurate
  selection of a clean text of the article without loss
- bulk processing URL at a time
