## 「World」是什么
- 世界是复杂的。
- 读初中时，历史课本里就有张骞使西域、丝绸之路的历史，从东方的长安到达西方的罗马，两个伟大的朝代通过一个美丽的名字联系在了一起，让人好奇，当长安人遇到金发碧眼的胡人女子时，会和十几年前的国人一样目光中满是稀奇吗。
- 汉魏时期把罗马称作大秦（《魏略》有云：“其人端正长大，衣服车旗拟仪中国，故外域谓之大秦”），后来又称阿拔斯为大食，到了唐时，极盛时期的东方唐廷和中东的阿拔斯竟然还爆发过战役（怛罗斯之战）。
-
- 每当读到以上种种，便会萌生一种想从时间和空间维度去了解世界和社会发展怎样演化的过程，不同地域之间是怎样进行交流、互相影响，然后发展成当下的这个社会。 同时感觉做出来这样一个东西一定很有意思。
-
- 启发之一是受到EU4之类的影响。
-
## 「World」
	- 这是一张全世界的地图，可以输入国家名称（中英文）定位到对应国家，有时间区间（具体日期）
	- 地图可以放大缩小，e.g. 放大是国家为单位，缩小是省份为单位。
	- 时间支持天/月/年为单位
	- 空间上最小的单位是省。
	- 支持编辑，因为非历史专业出身，个人编辑肯定不现实。
	- 地图的编辑：
		- 基于一个前提：不同时期、省份的所属是一定会变的。1644年前是明，之后是清。哪年哪月上海所属江苏道，后来又独立成了直辖市这样。比较稳定不变的只有地理板块。
			- 首先选择某个日期的地图，然后基于此地图进行（地理模块-省份）的重新划分和修改。形成新的地图，然后设置对应的时期（日/月/年）
			- 最初的地图只能自己动手了。
	- 地图编辑的函数和方法
		-
	- 前端渲染
-
## 关键词：echarts 地图
- echarts有地图数据，这周末看一下
- ![2021_08_18_image.png](https://cdn.logseq.com/%2F2bb51b82-34df-494a-8636-99e357d4bc2de9dfff24-c566-416c-9898-1b1e5505962a2021_08_18_image.png?Expires=4782870446&Signature=kCHVNhhMx2MxN0ZN5XK0KGYsEweIPxis7SeO1NtowwAbkcEbfFVXRyEbtmb0-zycD2SkXLJ5DNSsSBJGhJFiIogV2JRGZXuXSnYNHHgtHBCFxX~wZzDhkI3-3sui7rpiBNn5mqllocaDBqVPIsXmPIVzpqvxyej~RUwl4CcpP8c5dtWheg7BNlBRMPcZ8o~niHozchHzylt8GcZY0iUcnNYIm6LdA-TtDG~Lxr8n5JITEK7VwbZOYZf~QguY2Y7TQv-AFS0P649z6B9ik6aVQ7WSmoWlynddt0PfJ7pRXFulfjLgBAuLns~O1fd54ZOCSyMpHQsDC4T3mhWoT7AYPQ__&Key-Pair-Id=APKAJE5CCD6X7MP6PTEA) ![2021_08_18_image.png](https://cdn.logseq.com/%2F2bb51b82-34df-494a-8636-99e357d4bc2dce4946ef-95d1-4894-84d0-20506c6453fb2021_08_18_image.png?Expires=4782870446&Signature=UEzfF1OSAq0EzajvMadXoxKwVyeA8uErVWkaw1k3IasMnJv3I1Q~FEScKkaW6vUKRCNj1GySk1g5AuXFGXKWtzVUdFU9IDF3ZeMZ51W9XjUgfXmRxNlvKmp9WY0VWp-MmBOmISja~ugTe8Brh4M2oeq5BaI9zU0eXWLA31hfu9WhrDiosiUSlGhMEsVZx81mNBrdi0~vrs1E93F7Y9pEJ5-7M0kRFYnd2Su7W1o5ArZPmkTgaQn5wHb5NKGj2i8F1s0IO8MBUJj92sekUGme~sDDFGwGpXygeDOMWW0do7s146CLZMRODqztGbzCxQV5cTNaXJVZ2JwXZ~9dGSRuaQ__&Key-Pair-Id=APKAJE5CCD6X7MP6PTEA)
- ref：https://yezongyang.github.io/china-map/