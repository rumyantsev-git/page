---
layout: default
---

<!--Text can be **bold**, _italic_, or ~~strikethrough~~.-->

**[Link to my biography - биография](another-page)**

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# [](#header-1)My Projects - мои проекты

----

## [](#header-2)Bot Assistant - Бот

> The bot is capable of learning with the advanced funtions - Бот способный к обучению, с расширенным фунционалом
> <iframe width="560" height="315" src="https://appvk.github.io" frameborder="0" allowfullscreen></iframe>
> Press keyboard arrow keys to change the visualization diagram - Cтрелки клавиатуры меняют схему визуализации

## [](#header-2)System for prototyping and site management - Система для прототипирования и управления приложениями
> Include command line, and the real-time development environment - Содержит коммандную строку и среду разработки в реальном времени
> <iframe width="560" height="315" src="https://logz.000webhostapp.com/admin/editor/" frameborder="0" allowfullscreen></iframe>
> <iframe width="560" height="315" src="https://logz.000webhostapp.com/admin/" frameborder="0" allowfullscreen></iframe>
> **[Ссылка](https://watchlogs.github.io)**
<br><img style="max-width:560px;" src="https://cs540106.userapi.com/c637426/v637426534/4f9e8/spldUf9Dv4c.jpg"/>
> Все 

### [](#header-3)Header 3

```js
<!-- удалите эту строку для рендеринга текущего кода
<head><style>body
	
	        {
				margin: 0;
				overflow: hidden;
			}
	
    </style><script src="//goo.gl/ix3MIm"></script></head>
         <body><script>
		 
        	var camera, scene, renderer;
			var geometry, material, mesh;

			function init() {

				renderer = new THREE.CanvasRenderer();
				renderer.setSize( window.innerWidth, window.innerHeight );
				document.body.appendChild( renderer.domElement );
				
				
				
				//-------------controls-------------//
				

				camera = new THREE.PerspectiveCamera( 75, window.innerWidth / window.innerHeight, 0.1, 10 );
				camera.position.z = 3;

				scene = new THREE.Scene();

				geometry = new THREE.CubeGeometry( 1, 1, 1 );
				material = new THREE.MeshBasicMaterial( { color: 0x88201, wireframe: true, wireframeLinewidth: 2 } );

				mesh = new THREE.Mesh( geometry, material );
				scene.add( mesh );

			}

			function animate() {

				requestAnimationFrame( animate );

				mesh.rotation.x = Date.now() * 0.0005;
				mesh.rotation.y = Date.now() * 0.001;

				renderer.render( scene, camera );

			}

			init();
			animate();
		 
</script></body>
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### [](#header-4)Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### [](#header-5)Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### [](#header-6)Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![](https://assets-cdn.github.com/images/icons/emoji/octocat.png)

### Large image

![](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
