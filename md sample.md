---
tags:
  - sample
  - text
aliases:
  - text
---

1. Main 1
	- Sub 1
	- Sub 2
2. Main 2
	- [ ] To do 1
	- [x] To do 2

***

# Samples

## Fonts

*Italics*
**Bold**

***

### other

# h1
## h2
### h3
#### h4
##### h5
###### h6

5^2^ (= 5<sup>2</sup>)
H~2~O (= H<sub>2</sub>O)
~~crossed off~~
==highlight==
<u>underline</u>

***

> quote
>> quote in quote

***

This is a sample code. `git commit -m'text'`

This is a sample code block.
```python
print('Hello World!')
```

```html
<!DOCTYPE html>
<html lang="ja">
	<head>
		<meta charset="UTF-8">
		<meta name="viewport" content="width=device-width, initial-scale=1.0"> 
		<title>title</title> 
	</head> 
	<body> 
		<h1>Hello World!</h1>
		<p>sample</p> 
	</body> 
</html> 
```

```css
h1{
	color: #00ccff;
}

.a{
	color: #ff0000;
}
```

***

| Col 1  | Col 2  |   Col 3 |
|:------ |:------:| -------:|
| This's |   an   | Example |
| Table  |  for   | md_file |
| left   | center |   right |

$$
\int \log(\sin x) \,dx
$$

***

# [[md sample]]

[manim-color](https://docs.manim.community/en/stable/reference/manim.utils.color.manim_colors.html#module-manim.utils.color.manim_colors)

[[README]]

Tag: #tag

***

>[!note] callout
>This is a test.
>
>Supported types
>```
>[!note]
>[!abstract]
>	Aliases : summary, tldr
>[!info]
>[!todo]
>[!tip]
>	Aliases : hint, important
>[!success]
>	Aliases : check, done
>[!question]
>	Aliases : help, faq
>[!warning]
>	Aliases : caution, attention
>[!failure]
>	Aliases : fail, missing
>[!danger]
>	Alias : error
>[!bug]
>[!example]
>[!quote]
>	Alias : cite
>```

***

>[!note] Note

>[!abstract] Abstract
>	Aliases : summary, tldr

>[!info] Info

>[!todo] Todo

>[!tip] Tip
>	Aliases : hint, important

>[!success] Success
>	Aliases : check, done

>[!question] Question
>	Aliases : help, faq

>[!warning] Warning
>	Aliases : caution, attention

>[!failure] Failure
>	Aliases : fail, missing

>[!danger] Danger
>	Alias : error

>[!bug] Bug

>[!example] Example

>[!quote] Quote
>	Alias : cite

***

This is a footnote[^1].

[^1]: footnote
