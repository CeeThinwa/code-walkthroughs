# App Design

CREATE by fetching image from GitHub repo, and save as `ìmage` and `image_file_path`<br>
READ `ìmage` and/or `image_file_path`

CREATE by sending `image` and fetching `raw_text` from AWS Textract, duplicate `raw_text` as `clean_text`<br>
READ `clean_text`<br>
UPDATE `clean_text`

CREATE ElasticSearch database with `ìmage`, `image_file_path`, `raw_text`,`clean_text`<br>
DELETE `image`