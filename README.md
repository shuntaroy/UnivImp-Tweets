# UnivImp-Tweets
Japanese Tweet IDs of "universally important information"

普遍的重要情報ツイートデータセット（IDのみ）

## 概要

普遍的重要情報やそれを扱う2次的な言及をTwitter (現X)から収集した．2次的な言及（いわゆる「口コミ」）も集めるのは，普遍的重要情報が興味・関心外の受け手にとって，それらが受容しやすい可能性を考慮したからである．医療・災害に関する普遍的重要情報を発信するTwitterアカウントである警視庁警備部災害対策課（`@MPD_bousai`），警視庁生活安全部 （`@MPD_yokushi`），みんなで考える防災（`@nhk_ikiruskill`）を選定し，2015年から2022年までのツイートを収集した．さらに，収集されたツイートを「引用リツイート」している同期間のツイート（2次的言及）を芋づる式に取得した．

本データセットは [JSPS科研費 JP20K19932 「デジタル環境における偶然の情報遭遇を促すユーザインタフェースの設計と検証」](https://kaken.nii.ac.jp/ja/grant/KAKENHI-PROJECT-20K19932/) の成果として公開されたものである．

## CSV

- `quoting_tweet_id`
- `quoting_user_name`
- `quoted_tweet_id`
- `quoted_user_name`

## 統計

| ユーザ名             | ユーザID           | ツイート数 | 引用ツイート数 |
|---------------------|------------------|-----------|---------------|
| みんなで考える防災  | @nhk_ikiruskill  | 39        | 196           |
| 警視庁警備部災害対策課 | @MPD_bousai     | 950       | 23426         |
| 警視庁生活安全部     | @MPD_yokushi     | 84        | 284           |
