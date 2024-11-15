## Personal Toy Porjects 
<h3 id="shuttext" style="text-align: left !important;">1. <a href="https://github.com/XZJIsme/didide-BERT">Didide</a>: A toy project for Chinese character correcting
</h3>

<center>
<div style="text-align:center;">
    <img id="didide" src="/pics/abc-de-de-and-de.jpg" width="40%" style="border: 1.5px solid #ddd; margin:0 auto;" />
    <figcaption class="image-source" style="font-size: 0.8em; color: #999; text-align: center;">
        Image source: <a href="https://abcmandarinmission.wordpress.com/2013/02/08/saturday-grammar-the-differences-between-%E7%9A%84-de-%E5%9C%B0-de-and-%E5%BE%97-de/">ABC MANDARIN MISSION</a>
    </figcaption>
</div>

<script>
    var baseUrl_ = window.location.href.indexOf('localhost') !== -1
        ? 'http://localhost:1313'
        : 'https://xzjisme.github.io/zenga';
    var pic_didide = document.getElementById('didide');
    pic_didide.src = baseUrl_ + "/pics/abc-de-de-and-de.jpg";
</script>
</center>
 

<p id="didideinto">Didide is a project created by me to correct the misuse of the homophones 的, 地, and 得, which are often confused by beginners of Chinese and those who are careless. Source code can be found at <a href="https://github.com/XZJIsme/didide-BERT">GitHub</a>.</p>
<div class="highlight" style="width:100%;">
<pre tabindex="0" style="color:#181112;background-color:#f5f1ed;-moz-tab-size:4;-o-tab-size:4;tab-size:4;display: inline-block; width: 100%;">
<code class="language-bash" data-lang="bash"><span style="display:flex;"><span>python playground.py <span style="color:#6a2b14">"我觉的我烦的有点难过，因为我得培根忘记吃了"</span> <span style="color:#6a2b14">"didide_model.pt"</span>
</span></span><span style="display:flex;"><span><span style="color:#676767"># the output'd be: 我觉得我烦得有点难过，因为我的培根忘记吃了</span>
</span></span><span style="display:flex;"><span>python playground.py <span style="color:#6a2b14">"我觉的我烦的有点难过，因为我得培根忘记吃了，而且这种东西得营养一般般，但是好吃的哟！我天天早上开心的享受它的味道，开心的受不鸟哩！我咔咔的吃，吃的要满嘴流油 ，哈哈哈，痛快放肆的吃"</span> <span style="color:#6a2b14">"didide_model.pt"</span>
</span></span><span style="display:flex;"><span><span style="color:#676767"># the output'd be: 我觉得我烦得有点难过，因为我的培根忘记吃了，而且这种东西的营养一般般，但是好吃的哟！我天天早上开心地享受它的味道，开心得受不鸟哩！我咔咔地吃，吃得要满嘴流油，哈哈哈，痛快放肆地吃</span>
</span></span><span style="display:flex;"><span>python playground.py <span style="color:#6a2b14">"我要飛的更高，測試一下繁體預測的對不對，分類的還不錯"</span></span></span><span style="display:flex;"><span><span style="color:#676767"># the output'd be: 我要飛得更高，測試一下繁體預測的對不對，分類得還不錯</span></span></span><span style="display:flex;"><span><span style="color:#676767"># also works well with traditional Chinese. Yeah, it's because they have same input ids actually.
</span></span></span></code></pre></div>

The motivation for me to do the project was to try to make a real-world application with my software knowledge. Since the Chinese characters 的, 地, 得 share the same pinyin "de" in Mandarin, so it's easy to type wrong. The misuse of the three characters is very common on the Internet, sometimes even generating ambiguity. Though seems most people think that it's not a big deal, I still prefer using the correct grammar. So, I wrote this toy project. The project is not perfect, but it's still a good start for me to learn how to make a real-world application with programming.

<!-- ### 2. [Shutheblanksup: a VSCode extension](https://marketplace.visualstudio.com/items?itemName=createdforsbu.shutheblanksup) -->

<h3 id="shuttext" style="text-align: left !important;">
    2. <a href="https://marketplace.visualstudio.com/items?itemName=createdforsbu.shutheblanksup">Shutheblanksup: a VSCode extension</a> 
</h3>

<div  style="text-align:center;">
<!-- <center> -->
<!-- <div ">
    <h3 id="2-shutheblanksup-a-vscode-extension" ></h3>
</div> -->
<!-- </center> -->
<img id="shut" src="/pics/shutblanksup.png" width="8%" style="margin:0;" />
<script>
    var baseUrl_ = window.location.href.indexOf('localhost') !== -1
        ? 'http://localhost:1313'
        : 'https://xzjisme.github.io/zenga';
    var pic_shut = document.getElementById('shut');
    pic_shut.src = baseUrl_ + "/pics/shutblanksup.png";
</script>
</div>

 

When I first started programming, I didn't like the spaces that appeared after the IDE reformatted the code, so I wrote this extension, which can delete those spaces. But now I'm used to these spaces, in fact, I even write the spaces to format codes manually.

<div>
<center>
<div style="text-align:center;">
    <img id="shutblanksup" src="/pics/shutblanksup.gif" width="99%" style="margin:0 auto;" />
</div>
<script>
    var baseUrl_ = window.location.href.indexOf('localhost') !== -1
        ? 'http://localhost:1313'
        : 'https://xzjisme.github.io/zenga';
    var pic_shutblanksup = document.getElementById("shutblanksup");
    pic_shutblanksup.src = baseUrl_ + "/pics/shutblanksup.gif";
</script>
</center>
</div>

 


