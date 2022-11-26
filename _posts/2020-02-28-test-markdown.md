---
layout: post
title: Singly Linked list
subtitle: Detail explanation
gh-repo:  dsa-lab-assignment
gh-badge: [star, fork, follow]
tags: [test]
comments: true
---
**introduction:**
Single linked list is a linear data structure. It's elements are not stored in contiguous memory location like arrays. it is slightly different from array. it made by the nodes, each nodes consist a data and the address of the next node and each nodes are linked using pointers.

**Read further to learn more**

## Detail explanation

Table of content:

| S.No | Topic |
| :------ |:--- |
| 01 | creation of a node |
| 02 | insertion at begining |
| 03 | insertion at last |
| 04 | inserton at any position |




![Crepe]([https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg](https://www.sitesbay.com/data-structure/images/linked-list.png))

It can also be centered!

![Crepe]([https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg](https://res.cloudinary.com/dpessyoae/image/upload/v1494083335/linkedlist3_fsadk8.png)){: .mx-auto.d-block :}

Here's a code chunk:

~~~
struct Node
{
    int data;
    struct Node *next;
};
~~~

And here is the same code with syntax highlighting:

```javascript
struct Node
{
    int data;
    struct Node *next;
};
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
struct Node
{
    int data;
    struct Node *next;
};
{% endhighlight %} 

## Boxes
---------------------------------

### Notification

{: .box-note}
**Note:** Comming Soon.

### Warning

{: .box-warning}
**Warning:** Working.

### Error

{: .box-error}
**Error:** Not completed.
