---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Delta Refactoring for Merge Conflict Avoidance"
subtitle: ""
summary: "Long paper at ISEC 2016"
authors: [D. Saha, P. Dhoolia, M. Garg, Vaibhav]
tags: []
categories: []
date: 2016-04-10T20:26:25-04:00
lastmod: 
featured: false
draft: false
url_pdf: "https://researcher.watson.ibm.com/researcher/files/in-diptsaha/delta.pdf"
url_code: ""
abstract: "Today's software are developed and maintained by multiple developers. A particular source code can be updated from multiple sources which can possibly lead to a conflict. Manual resolution of such conflict is time consuming and error prone. Various frameworks address this problem in different ways - some define guidelines or contracts to avoid such conflict, others use powerful merge tools to automatically resolve the conflicts. We observe that in many cases the conflicts are due to identical update locations. Such a conflict can be avoided if the change is performed in some other location. In this paper we developed Delta Refactoring, a set of semantic preserving program transformations to move a change to a safe location - either following the guidelines or outside the conflict region determined by the text-based merging tool. Our main motivation is to solve a problem in SAP-ERP domain where conflicts occur during the merge of SAP updates and custom enhancements. We also demonstrate the effectiveness of our solution in the context of diff3 based textual merge used in source code management systems.
"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
