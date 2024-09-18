<script>
    // import the formateDate function defined in clientFunctions.js
    //import { formatDate } from '$lib/clientFunctions.js';
    
    // This allows access to the data exported from +page.server.js 
    export let data;
	const { articles } = data;    

</script>

<!-- <h2>Irish Times</h2> -->
<div id="stories" />
<div class="container">
    <div id="articles">
        <!-- a Svelete for each to iterate through articles -->
        {#each articles as article }
        <div class="front_page">
            <div class="article_details">
            <h2><a href='{article.url}'>{article.title}</a></h2>
            <h6>{article.author}</h6>
            <!-- format the date using function -->
            <!-- <h6>{article.publishedAt}</h6> -->
            <p>{article.description}</p>
            <h6><a href='{article.url}'>Read More</a></h6>
            </div>
            <div class="article_img">
                <a href='{article.url}'><img src={article.urlToImage} alt="caption"></a>
            </div>
          </div>
    {/each}
    </div>

    <aside class="sidebar">
        <h2>Top Stories</h2>
        {#each articles as article }
        
            <div class="sidebar_details">
            <h6>{article.author}</h6>
            <h4><a href='{article.url}'>{article.title}</a></h4>
            <!-- <p>{article.author}</p> -->
            <!-- format the date using function -->
            <!-- <p>{article.publishedAt}</p> -->
         
            
            </div>
            <div class="article_img">
                <a href='{article.url}'><img src={article.urlToImage} alt="caption"></a>
            </div>
         
    {/each}
    </aside>
</div>


<footer>
    <p>
        Powered by <a href="https://newsapi.org/">https://newsapi.org/</a>
    </p>
</footer>
