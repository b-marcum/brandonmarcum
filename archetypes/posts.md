---
title: "{{ replace .Name "-" " " | title }}"
description: "Desc Text."
date: {{ .Date }}
draft: true
# weight: 1
# aliases: ["/first"]
tags: [""]
author: "Brandon Marcum"
# author: ["Me", "You"] # multiple authors
showToc: false
TocOpen: false
hidemeta: false
comments: false
canonicalURL: "https://www.brandonmarcum.net/posts/2023/{{ .Name }}"
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true
cover:
    image: "<image path/url>" # image path/url
    alt: "<alt text>" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
# editPost:
#     URL: "https://github.com/b-marcum/brandonmarcum/tree/content"
#     Text: "Suggest Changes" # edit text
#     appendFilePath: true # to append file path to Edit link
---
