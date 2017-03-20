# search-filter
Search on the web has gone far beyond simply going to search engines to find information. In order to dig deeper and find content more relevant to search queries, website visitors are increasingly searching through actual websites themselves for that right piece of content they're looking for. 

To take that a step further, it is possible to add filters to your search inputs so your website visitors can further specify the content they are looking for. This allows you to deliver a better web experience that provides the visitor with the content they are looking for at a much faster rate.  In this tutorial, we will teach you how to add a category filter to your search input to provide more relevant search results to website visitors.

## Tutorial

For detailed instructions, view Solodev's [Adding a Filter to your Search Input using Bootstrap](https://www.solodev.com/blog/web-design/adding-a-filter-to-your-search-input-using-bootstrap.stml) article.

## Demo

Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/m7d3csmm/).

## HTML

The search filter contains the following basic HTML markup.

```
<div class="container">
  <div class="row searchFilter" >
     <div class="col-sm-12" >
      <div class="input-group" >
       <input id="table_filter" type="text" class="form-control" aria-label="Text input with segmented button dropdown" >
       <div class="input-group-btn" >
        <button type="button" class="btn btn-secondary dropdown-toggle dropdown-toggle-split" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false" ><span class="label-icon" >Category</span> <span class="caret" >&nbsp;</span></button>
        <div class="dropdown-menu dropdown-menu-right" >
           <ul class="category_filters" >
            <li >
             <input class="cat_type category-input" data-label="All" id="all" value="" name="radios" type="radio" ><label for="all" >All</label>
            </li>
            <li >
             <input type="radio" name="radios" id="Design" value="Design" ><label class="category-label" for="Design" >Design</label>
            </li>
            <li >
             <input type="radio" name="radios" id="Marketing" value="Marketing" ><label class="category-label" for="Marketing" >Marketing</label>
            </li>
            <li >
             <input type="radio" name="radios" id="Programming" value="Programming" ><label class="category-label" for="Programming" >Programming</label>
            </li>
            <li >
             <input type="radio" name="radios" id="Sales" value="Sales" ><label class="category-label" for="Sales" >Sales</label>
            </li>
            <li >
             <input type="radio" name="radios" id="Support" value="Support" ><label class="category-label" for="Support" >Support</label>
            </li>
           </ul>
        </div>
        <button id="searchBtn" type="button" class="btn btn-secondary btn-search" ><span class="glyphicon glyphicon-search" >&nbsp;</span> <span class="label-icon" >Search</span></button>
       </div>
      </div>
     </div>
  </div>
</div>
```
## CSS

All required CSS is contained in search-filter.css

## External Includes

This tutorial contains the following third party resources.

```
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" rel="stylesheet">
<link href="search-filter.css" rel="stylesheet">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
```
