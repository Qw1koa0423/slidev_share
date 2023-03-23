---
theme: prussianblue
contents: 
- SpaceSniffer
- Snipaste
- Everything
- Utools
- Tampermonkey
- End
	
---

<div v-click='1'>

<div
v-motion
:initial="{ opacity: 0, scale: 0.75,y: 100 }"
:visible="{ opacity: 1, y: 0, scale: 1 ,transition: {
type: 'spring',
}}"
:hovered="{ scale: 1.2 }"
>
		
# 原来你的电脑还可以这样玩！
</div>

<div
v-motion
:initial="{ opacity: 0, x: 300 }"
:visible="{ opacity: 1, x: 0, scale: 1 ,transition: {
type: 'spring',
delay: 1200,
}}"
:hovered="{ scale: 1.2,delay: 100 }"
>

神器插件大集合：提高生产力的利器
</div>

<div 
v-motion
:initial="{ opacity: 0, x: -300 }"
:visible="{ opacity: 1, x: 0, scale: 1 ,x: 0,transition: {
type: 'spring',
delay: 1600,
}}"
:tapped="{
x: 300,
opacity: 0.1,
scale: 1.2,
transition: {
type: 'spring',
}}"
class="pt-12">
  <span @click="next" class="px-2 p-1 rounded cursor-pointer hover:bg-white hover:bg-opacity-10">
    一键操作，轻松搞定复杂任务 <carbon:arrow-right class="inline"/>
  </span>
</div>
</div>

---
id: 1
---

<div
class='overflow-auto max-h-425px'
>

<div
v-click='1'
v-motion
:initial="{ opacity: 0, y: -10 }"
:visible="{ opacity: 1, y: 0, scale: 1 ,transition: {
type: 'spring',
}}"
>

# 是谁在浪费我的硬盘空间
</div>
<div
v-motion
:initial="{ opacity: 0,scale: 0.1, y: -10 }"
:visible="{ opacity: 1, y: 0, scale: 1 ,transition: {
type: 'spring',
}}"
>

### 你是否遇到过这种情况?

<img src='/SpaceSniffer_1.png' class='w-4/5 mx-auto' />

</div>
<div
v-click='2'
v-motion
:initial="{ opacity: 0, y: 100 }"
:visible="{ opacity: 1, y: 0, scale: 1 ,transition: {
type: 'spring',
}}"
>

## 硬盘空间分析器-SpaceSniffer

- 电脑存储空间似乎总是不够用，每次都让我们感到苦恼。但是有了SpaceSniffer，这个问题就可以轻松解决啦！SpaceSniffer是一款功能强大的磁盘空间分析工具，它可以帮助你检查电脑上每一个文件夹和文件的大小，并以直观的方式展示给你。只需一眼就能看出哪些文件占用了大量的空间！除此之外，SpaceSniffer还支持多种图表和颜色方案，让你可以更加方便地了解电脑存储空间的情况，而且数据导出和快速定位功能更是让你轻松管理和利用电脑存储空间。总之，如果你需要一个高效、实用的磁盘空间分析工具，SpaceSniffer绝对值得一试。
</div>
<div
v-click='3'
v-motion
:initial="{ opacity: 0, x: 500 }"
:visible="{ opacity: 1, x: 0, scale: 1 ,transition: {
type: 'spring',
}}"
>

<video src="/SpaceSniffer.mp4" controls class="mx-auto" />
	
</div>
</div>

---
id: 2
---

<div
class='overflow-auto max-h-425px'
>
<div
v-click='1'
v-motion
:initial="{ opacity: 0, y: -10 }"
:visible="{ opacity: 1, y: 0, scale: 1 ,transition: {
type: 'spring',
}}"
>

# 重生之我是截图界大佬
</div>

<div
class='flex-col space-y-4'
>
<div
v-motion
:initial="{ opacity: 0, y: -15 }"
:visible="{ opacity: 1, y: 0, scale: 1 ,transition: {
type: 'spring',
}}"
>

### 你是否还在使用微信、QQ甚至Win+Shift+S这些古老的方式截图?
</div>

<div
v-motion
:initial="{ opacity: 0, x: 500 }"
:visible="{ opacity: 1, x: 0, scale: 1 ,transition: {
type: 'spring',
delay: 500,
}}"
>

<img src='/Snipaste_1.png' class='w-4/5 mx-auto' />
</div>
<div
v-motion
:initial="{ opacity: 0, x: -500 }"
:visible="{ opacity: 1, x: 0, scale: 1 ,transition: {
type: 'spring',
delay: 1000,
}}"
>

<img src='/Snipaste_2.png' class='w-4/5 mx-auto' />
</div>
<div
v-motion
:initial="{ opacity: 0, y: 100 }"
:visible="{ opacity: 1, y: 0, scale: 1 ,transition: {
type: 'spring',
delay: 1500,
}}"
>

<img src='/Snipaste_3.png' class='w-4/5 mx-auto' />
</div>
</div>

<div
v-click='3'
v-motion
:initial="{ opacity: 0,scale: 0 }"
:visible="{ opacity: 1,  scale: 1 ,transition: {
type: 'spring',
}}"
class='mt-12'
>

## 有了Snipaste，我终于成为了截图界的大佬

- 截图好帮手，来自Snipaste！这款功能强大的截图工具不仅支持全屏截图和窗口截图，还可以将截图自动粘贴到画板上进行编辑。您可以在截图时添加文字、标注和形状等，表现更加灵活。而且Snipaste也很人性化，它还支持自定义快捷键，让你可以更加方便地使用这个工具。无论是工作还是日常生活，Snipaste都能够帮你变成一个截图界的大佬！
</div>

<div
v-click='2'
v-motion
:initial="{ opacity: 0, x: 500 }"
:visible="{ opacity: 1, x: 0, scale: 1 ,transition: {
type: 'spring',
}}"
>

<video src="/Snipaste.mp4" controls ></video>
</div>
</div>

---
id: 3
---
<div
class='overflow-auto max-h-425px'
>

<div
v-motion
:initial="{ opacity: 0, y: -10 }"
:visible="{ opacity: 1, y: 0, scale: 1 ,transition: {
type: 'spring',
delay: 3200,
}}"
>

# 谁说找东西要靠感觉？
</div>

<div class='flex space-x-2 w-auto'>
<div
v-motion
:initial="{ opacity: 0, x: -100 }"
:visible="{ opacity: 1, x: 0, scale: 1 ,transition: {
type: 'spring',
delay: 800,
}}"
>

### 你是否曾因为不记得某个文件放在了哪里而苦思冥想？
<img src='/Everything_1.png' class='w-4/5 mx-auto' />
</div>
<div
v-motion
:initial="{ opacity: 0, y: 100 }"
:visible="{ opacity: 1, y: 0, scale: 1 ,transition: {
type: 'spring',
delay: 2400,
}}"
>

### 你是否因为电脑文件夹太多而感到心烦意乱？
<img src='/Everything_3.png' class='w-4/5 mx-auto' />
</div>
<div
v-motion
:initial="{ opacity: 0, x: 50 }"
:visible="{ opacity: 1, x: 0, scale: 1 ,transition: {
type: 'spring',
delay: 1600,
}}"
>

### 你是否又因为常常找不到文件而感到焦虑不安？
<img src='/Everything_2.png' class='w-4/5 mx-auto' />
</div>
</div>
<div
v-click='1'
>
<div
class='grid grid-cols-4'
>
<div
v-motion
:initial="{ opacity: 0, scale: 0 }"
:visible="{ opacity: 1, scale: 1 ,transition: {
type: 'spring',
}}"
class='col-span-3 flex items-center pr-12 leading-loose'
>
<div>

## Everything-让你在电脑上飞快地找到每一个文件

- 曾经因为找不到一个文件而心烦意乱过吗？everything是你的好朋友！everything是一款快速的文件搜索工具，它可以在几秒钟内查找你电脑上的任何文件或者文件夹，甚至可以快速定位你正在使用的软件。说再见吧，以前那种死等电脑响应的时候！everything不仅速度快、操作简单，而且支持多种文件格式和搜索选项，让你可以更加灵活地定位你想要寻找的内容。所以，不管你需要找哪个文件，everything都是你的坚实后盾！
</div>
</div>
<div
v-click='2'
v-motion
:initial="{ opacity: 0, x: 10 }"
:visible="{ opacity: 1, x: 0, scale: 1 ,transition: {
type: 'spring',
}}"
class='col-span-1'
>
<video src="/Everything.mp4" controls></video>
</div>

</div>
</div>
</div>

---
id: 4
---

<div
class='overflow-auto max-h-425px'
>
<div
v-motion
:initial="{ opacity: 0, y: -10 }"
:visible="{ opacity: 1, y: 0, scale: 1 ,transition: {
type: 'spring',
}}"
>

# 与其说是工具，不如说是魔法
</div>

<div
v-click='1'
>
<div
v-motion
:initial="{ opacity: 0, x: -30 }"
:visible="{ opacity: 1, x: 0, scale: 1 ,transition: {
type: 'spring',
delay: 2000,
}}"
>

## utools大闸蟹助你轻松上岸
</div>
<div
v-motion
:initial="{ opacity: 0, scale: 0 }"
:visible="{ opacity: 1, scale: 1 ,transition: {
type: 'spring',
delay: 100,
}}"
>

- 想要成为电脑操作高手吗？那就必须要有utools！这是一款智能化的工具集，里面包含了众多实用工具和服务，可以帮助你更加高效地完成各种任务。无论是日常工作还是生活，都能够让你事半功倍！其中，utools最大的特点是它具备智能搜索和联想功能，让你可以通过简单的关键词搜索就能快速找到你需要的内容。而且utools还支持各种插件和扩展，帮助你组织和管理你的工作和生活。
</div>
</div>
<div
v-click='2'
v-motion
:initial="{ opacity: 0, y: 300 }"
:visible="{ opacity: 1, y: 0, scale: 1 ,transition: {
type: 'spring',
delay: 400,
}}"
>
 <video src="/utools.mp4" controls ></video>	
</div>
</div>
---
id: 5
---

<div
class='overflow-auto max-h-425px'
>
<div
v-motion
:initial="{ opacity: 0, y: -10 }"
:visible="{ opacity: 1, y: 0, scale: 1 ,transition: {
type: 'spring',
}}"
>

# 把互联网打造成你想要的模样
</div>

<div
 v-motion
 :initial="{ opacity: 0,scale: 0}"
 :visibleOnce="{ opacity: 1, scale: 1 ,transition: {
 type: 'spring',
 delay: 400,
 }}"
 class='text-center'>

### 你是否常常因为下饭剧的冗长开头广告而感到无聊和烦躁？
<div
class='grid grid-cols-2 gap-4'
>
<div
v-motion
:initial="{ opacity: 0, y: 100,x: -100 }"
:visibleOnce="{ opacity: 1, y: 0,x: 0, scale: 1 ,transition: {
type: 'spring',
 delay: 1500,
}}"
>
<img src='/gg_1.png' class='mx-auto' />

</div>
<div
v-motion
:initial="{ opacity: 0, y: -100,x: 100 }"
:visibleOnce="{ opacity: 1, y: 0,x: 0, scale: 1 ,transition: {
type: 'spring',
delay: 1500,
}}"
>
<img src='/gg_2.png' class='mx-auto' />
</div>
</div>
</div>
<div
class='p-6'
v-click='2'
v-motion
:initial="{ opacity: 0,scale: 0}"
:visibleOnce="{ opacity: 1, scale: 1 ,transition: {
type: 'spring',
}}">

<img src='/gg_3.jpg' class='mx-auto w-2/3' />
</div>
<div
v-click='3'
v-motion
:initial="{ opacity: 0, scale: 0 }"
:visible="{ opacity: 1, scale: 1 ,transition: {
type: 'spring',
}}"
:hovered="{
    scale: 1.5,
}"
class='text-center'
>

## Tampermonkey助力每一个追梦人
</div>
<div
v-click='1'
v-motion
:initial="{ opacity: 0,scale: 0,  }"
:visibleOnce="{ opacity: 1, scale: 1 ,transition: {
type: 'spring',
delay: 800}}"
class='text-center pb-12'>

### 你是否因为大厂的吃相难看而又无可奈何？
<div
class='grid grid-cols-4 gap-2'
>
<div
v-motion
:initial="{ opacity: 0, x: -100 }"
:visibleOnce="{ opacity: 1, x: 0, scale: 1 ,transition: {
type: 'spring',
 delay: 1500,
}}"
>
<img src='/vip_1.png' class='mx-auto' />

</div>
<div
v-motion
:initial="{ opacity: 0, y: -100 }"
:visibleOnce="{ opacity: 1, y: 0, scale: 1 ,transition: {
type: 'spring',
delay: 2500,
}}"
>
<img src='/vip_2.png' class='mx-auto' />
</div>
<div
v-motion
:initial="{ opacity: 0, y: 80 }"
:visibleOnce="{ opacity: 1, y: 0, scale: 1 ,transition: {
type: 'spring',
delay: 2500,
}}"
>
<img src='/vip_3.png' class='mx-auto' />
</div>
<div
v-motion
:initial="{ opacity: 0, x: 100 }"
:visibleOnce="{ opacity: 1, x: 0, scale: 1 ,transition: {
type: 'spring',
delay: 1500,
}}"
>
<img src='/vip_4.png' class='mx-auto' />
</div>
</div>
</div>


</div>

---
id: 6
---

<div
class='overflow-auto max-h-425px'
>
<div
v-motion
:initial="{ opacity: 0, y: -10 }"
:visible="{ opacity: 1, y: 0, scale: 1 ,transition: {
type: 'spring',
delay: 1000,
}}"
class='text-center'
>

# 看到End你以为这就结束了？
</div>

<div
class='flex space-x-6 justify-around'
>

<div
v-motion
:initial="{ opacity: 0, x: -30 }"
:visible="{ opacity: 1, x: 0, scale: 1 ,transition: {
type: 'spring',
delay: 1800,
}}"
>

<img src='/pnd.jpg' class='mx-auto' />
</div>
<div
v-motion
:initial="{ opacity: 0, x: 30 }"
:visible="{ opacity: 1, x: 0, scale: 1 ,transition: {
type: 'spring',
delay: 3000,
}}"
>

<img src='/mxdb.jpg' class='mx-auto' />
</div>

</div>

<div
v-motion
:initial="{ opacity: 0,  scale: 0 }"
:visible="{ opacity: 1,  scale: 1 ,transition: {
type: 'spring',
delay: 4500,
}}"
class='text-center'
>

## 让我们请一位神秘嘉宾来分享一下他的神器吧!
</div>

<div
v-motion
:initial="{ opacity: 0,  y: 20 }"
:visible="{ opacity: 1, y: 0, scale: 1 ,transition: {
type: 'spring',
delay: 5500,
}}"
>
<img src='/smr.jpeg' class='mx-auto' />
</div>

</div>
