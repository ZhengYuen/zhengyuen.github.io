# Jekyll notes
# 1. Front Matter
> follow https://jekyllrb.com/docs/installation/
```
# Switch to China Source.
gem sources --remove https://rubygems.org/
gem sources --add https://gems.ruby-china.com/ 
```
# 2. Front Matter
Variables:
```
---
layout: layout_template
tags: tag_1 tag_2 tag_3
<your_var>: my_var
---
```
#  3. Post and Page
# Post
>>```
>>{% for tag in post.tags %}
>>    <a href="#">{{ tag }}</a>
>>{% endfor%}
>>```