# README

#### Custom json structure (basically the same as the original json, delete the desc introduction, and add filter grouping):
```json
    [{
    "_id": "", //分类简称
	"classify": "", //分类名称
    "icon": "", //分类图标 基于themify-icons
    "filter": "",//分类筛选
	"sites": [{
		"name": "", //网站名
		"href": "",//网站链接
		"logo": "" //网站logo
        }]
    }]
```
#### Custom json structure description:
The main goal is to separate work from daily life and use different json or categories on work computers and personal computers;
You can use different json addresses, or use different filters to distinguish the same json address;
Multiple categories can be grouped using the same filter

#### Cross-domain description of custom parameter address:
If you use someone else to build or debug the page locally, and the custom URL and the navigation page URL are not under the same domain name, you must enable cross-domain access for the custom URL;
- The json hosted on github can directly obtain the raw address for reference;


TODO：
- [x] The URL is accessed with json address parameters (convenient to display some inconvenient items or display on demand);

- [ ] Widget (current URL generates QR code, current URL generates short URL);

- [ ] Customized addition of local bookmarks;



# Other instructions: 

- The category title icon in json comes from the font icon library [themify-icons](https://themify.me/themify-icons);
- This project is open source based on the MIT license.
