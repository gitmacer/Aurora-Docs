---
layout: doc
title: Various Elements Test
order: 3
authors:
  - Wibble199
  - diogotr7
---

# Horizontal Rule

Before rule

---

After rule

# Large Paragraph

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas elementum euismod mattis. Etiam fringilla pharetra volutpat. Nullam pretium, mi ac dignissim lacinia, quam sapien sollicitudin elit, ut ultrices mi nisi non ligula. Donec in blandit erat. Nunc lacinia tincidunt leo, id tincidunt turpis pellentesque at. Pellentesque id massa sapien. Etiam ut volutpat neque. Vivamus tincidunt dui vel eros pellentesque, posuere interdum neque gravida. Integer tristique orci ac lectus varius, vel dictum odio ornare. Duis et iaculis felis, porttitor egestas ex. Sed consequat elementum felis, et tincidunt arcu rhoncus vitae. Mauris sed ante ac purus blandit pellentesque id sit amet urna. Praesent auctor vestibulum augue, at eleifend odio euismod in. Morbi mollis orci quis euismod finibus. Curabitur porta finibus molestie. Sed a erat malesuada, placerat massa condimentum, convallis mauris. 

Some text [with a link](http://www.project-aurora.com/) in it.

# Code Test

Before code

```cs
public class Test {
  public int Lol { get; set; }

  public Test() {
    Lol = 5;
    System.Console.WriteLine("Test");
  }

  private int LigatureTest => Lol;
}
```

After code

# List

Before list

- Item 1
	- Nested
- Item 2
- Item 3

1. Numbered 1
	1. Nested
2. Numbered 2
3. Numbered 3

After list

# Table

Before table

A|B|Longer Header
-|-|-
a|b|Which has longer content
1|2|Not much longer, but a bit longer

After table

# Image

Images should be placed in `assets/img`.

![If alt text is provided, it will appear as a caption](/assets/img/temp.png)

![](/assets/img/wide.png)

After image