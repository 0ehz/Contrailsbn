
# recordName

> This is the feed's ID which can be letters, numbers, or dashes. Spaces are not allowed. Maximum length is 15 characters.

bnsisyo-list

# displayName

> This is the title of the custom feed. Maximum length is 24 characters.

文司書

# description

> This is the description of the feed.

「文シショ」「ぶんししょ」「ブンシショ」が含まれているpostを自動で拾うフィードです。※「○○シショ ( CP表記 ) 」も拾います。現在89CP取得中。※一般検索の観点からシショの漢字表記は含めていません。

# searchTerms

> There are three types of search terms:
>
> - Keywords: Test these in [https://bsky.app/search](https://bsky.app/search). `AND` is implicit, so `cat dog` on one line will require both `cat` and `dog`. You can use quotes as well `"hot dog"`.
> - Users: links such as `https://bsky.app/profile/why.bsky.team` will pull in the user's posts. To include replies and reposts, you can add the following flags: `https://bsky.app/profile/why.bsky.team +replies +reposts`.
> - Pinned posts: links such as `https://bsky.app/profile/saddymayo.bsky.social/post/3jxju2wwap22e` will pin at the top of the feed. One link per line, please.

- https://bsky.app/profile/0ehz.relizard.net/post/3kh27ynjad32k
- "文シショ"
- "ブンシショ"
- "ぶんししょ"
- "芥シショ"
- "夢シショ"
- "乱シショ"
- "安シショ"
- "清シショ"
- "太シショ"
- "朔シショ"
- "中シショ"
- "鏡シショ"
- "夏シショ"
- "賢シショ"
- "谷シショ"
- "荷シショ"
- "藤シショ"
- "花シショ"
- "志賀シショ"
- "しがししょ"
- "シガししょ"
- "森シショ"
- "川シショ"
- "白シショ"
- "犀シショ"
- "梶シショ"
- "広シショ"
- "武者シショ"
- "むしゃシショ"
- "紅シショ"
- "四シショ"
- "有シショ"
- "春シショ"
- "多喜シショ"
- "鱒シショ"
- "横シショ"
- "織田シショ"
- "堀シショ"
- "敦シショ"
- "八シショ"
- "規シショ"
- "牧シショ"
- "高シショ"
- "啄シショ"
- "独シショ"
- "露シショ"
- "譲シショ"
- "吉シショ"
- "山シショ"
- "粂シショ"
- "直シショ"
- "重シショ"
- "泡シショ"
- "鳥シショ"
- "蘆シショ"
- "植シショ"
- "介シショ"
- "寛シショ"
- "さちシショ"
- "ろふシショ"
- "三シショ"
- "新シショ"
- "未シショ"
- "勇シショ"
- "種シショ"
- "放シショ"
- "美シショ"
- "三重シショ"
- "百シショ"
- "茂シショ"
- "草シショ"
- "弴シショ"
- "折シショ"
- "柳シショ"
- "檀シショ"
- "高シショ"
- "碧シショ"
- "透シショ"
- "秋シショ"
- "トルシショ"
- "ドスシショ"
- "ゲシショ"
- "ボドシショ"
- "ランシショ"
- "ヘミシショ"
- "フィシショ"
- "ポシショ"
- "ハワシショ"
- "コナシショ"
- "ルイシショ"
- "ネコシショ"
- "館シショ"

# denyList

> Deny list will exclude any results from a given user. You can provide the username or DID.
>
> - did:plc:1234
> - @spamspamspam.bsky.social

# safeMode

> Safe mode limits the total number of API calls coming from Cloudflare.
>
> Set to `false` if you have higher limits via a paid Cloudflare plan.

true

# avatar

> This must link to an image (PNG or JPEG) in the same directory as this CONFIG.md. It doesn't have to be called `avatar.png`, but just be sure this CONFIG.md points to the correct file.

![](book4.jpg)
