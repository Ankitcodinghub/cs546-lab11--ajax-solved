# cs546-lab11--ajax-solved
**TO GET THIS SOLUTION VISIT:** [CS546 Lab11 -AJAX Solved](https://www.ankitcodinghub.com/product/cs546-lab11-ajax-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91588&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS546 Lab11 -AJAX Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<table>
<tbody>
<tr>
<td></td>
</tr>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
CS-546 Lab 11 AJAX

For this lab, you will be using HTML, JQuery and Client-side JavaScript on the user’s browser to make a simple application that makes AJAX requests for the data needed and then inject the elements and data onto the page.

TV Maze API

For this lab, you will be using three endpoints of the TV Maze API for your AJAX calls. The list of shows: http://api.tvmaze.com/shows (http://api.tvmaze.com/shows) and then you’ll get an individual show

using the endpoint http://api.tvmaze.com/shows/:id (http://api.tvmaze.com/shows/:id) where :id is the ID of the show you are looking up. You will also use http://api.tvmaze.com/search/shows? q=search_term (http://api.tvmaze.com/search/shows?q=search_term) to search the API

The Server

Your server this week should not do any of the processing or calculations. Your server only exists to allow someone to get to the HTML Page and download the associated assets to run the application.

/ TheWholeApplication

This route will respond with a static HTML file and all of the functionality will be done in a client-side JS file. You will make client-side AJAX requests to the API and use jQuery to target and create elements on the page.

Your page should have a few basic user interface elements:

A header tag, with an h1 naming your site, with a title for your page

A footer with your name, student ID, and any other info about yourself you wish to include An empty unordered list with an id of showList that is initially hidden.

A div with an id of show that is initially hidden.

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
https://sit.instructure.com/courses/50148/assignments/273381

</div>
<div class="column">
1/5

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
12/14/21, 11:47 PM Lab 11

A form with an id of

A text input with an id of

A label with a for attribute referencing your input

A button to submit the form

A link that links back to the “/” route with the text “Back to All Shows” and that has an id of

This link will initially be hidden. It will ONLY be displayed when the show element is being displayed or ONLY when a search is performed and search results are being displayed. You should NOT show this link on the initial show list. This link will simply trigger a reload of the page, which then will display the initial list of shows

AJAX Requests

Remember, you will be ONLY using client-side JavaScript!

1. Page load: When the page loads, you will query the TV Maze API to get the list of shows using an AJAX request. Once the AJAX request returns the data, you will then create list items of links for each show that is returned using jQuery. The link text will be the name of the show, and the href attribute will be set to the url for that show from the TV Maze API (the url we need for the link is in the data, in the

field.) For the link, you will need to call a function on the click event of the link (do not forget to preventDefault() for the default behavior for the link. You will then append each list item to the

UL element and then show the element (make sure you hide the show element). Endpoint to be used: http://api.tvmaze.com/shows (http://api.tvmaze.com/shows)

2. Search Form Submission: If there is no value for the input when the form is submitted, you should not continue and instead should inform them of an error somehow. (don’t forget to take into account if they just submit the form with a bunch of spaces as the value!) If there is a value, you will first empty the list item elements in the element (because there will be elements from the initial showList still there, they are just hidden), then query the API for that using an AJAX request. Once the AJAX request returns the data, you will then create list items of links for each show that is returned using jQuery. The link text will be the name of the show, and the href will link to the url for that show. (the url we need is in the data in the field. You will then append each list item to the UL element and then show the element (make sure you hide the

show element).

Endpoint to be used: http://api.tvmaze.com/search/shows?q=search_term_here

(http://api.tvmaze.com/shows)

3. Link Clicked: For the link, you will need to call a function on the click event of the link and not the default link behavior (do not forget to use preventDefault()). When the link to a show is clicked, it will hide the element, it will then empty the show element (just in case there was show data previously loaded into the show element). It will then make an AJAX request to the URL and fetch the data for that show (that was the href in your link). You will parse through the show data returned from

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
searchForm.

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>search_term.
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
homeLink

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>_links.self.href
showList
</pre>
</div>
<div class="column">
showList

showList

</div>
</div>
<div class="layoutArea">
<div class="column">
search_term

search_term

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>_links.self.href
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
showList

showList

</div>
</div>
<div class="layoutArea">
<div class="column">
showList

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
https://sit.instructure.com/courses/50148/assignments/273381 2/5

</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
12/14/21, 11:47 PM Lab 11

the AJAX request. You will create the following elements using jQuery: an h1 with the show name , an img which the src is set to the value read from in the data which is a URL to an image

for the show, and a dl (definition list) of the following properties of the matching show: language , (the entire array in an ul ), , , and You will then show

the show element.

NOTE: Not all shows have ALL data displayed on the show element, which will cause your application to not work correctly when a show link is clicked if it doesn’t have all the needed data needed for the show element. You will be required to check each field needed for the

show element. If there is no value for a field, you will show “N/A” instead of that field’s value on the show detail element. For the image, if there is no image, you can load a generic “no image” image that is served from your public directory. You can save this one (right click and save the image):

For example: The show “Hemlock Grove” is missing the network, “Anna und die Haustiere” is missing the image and the Average Rating, “Under Arrest” is missing the Language, the Average Rating and the Network. You would display them similar to shown below.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
image.medium

genres rating.average network.name summary.

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
https://sit.instructure.com/courses/50148/assignments/273381 3/5

</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="layoutArea">
<div class="column">
12/14/21, 11:47 PM Lab 11

</div>
</div>
<div class="layoutArea">
<div class="column">
https://sit.instructure.com/courses/50148/assignments/273381

</div>
<div class="column">
4/5

</div>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="section">
<div class="layoutArea">
<div class="column">
12/14/21, 11:47 PM Lab 11

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Endpoint to be used: http://api.tvmaze.com/shows/:id (http://api.tvmaze.com/shows) (this is read from the href attribute of the link)

Style:

You are NOT required to use CSS for this lab (but you can if you want to).

Requirements

1. All previous requirements still apply.

2. You must remember to update your package.json file to set app.js as your starting script!

3. Your HTML must be valid (https://validator.w3.org/#validate_by_input) or you will lose points on the

assignment.

4. Your HTML must make semantical sense; usage of tags for the purpose of simply changing the style

of elements (such as i , b , font , center , etc) will result in points being deducted; think in terms of

content first.

5. You can be as creative as you’d like to fulfill front-end requirements; if an implementation is not

explicitly stated, however you go about it is fine (provided the HTML is valid and semantical). Design

is not a factor in this course.

6. Your client side JavaScript must be in its own file and referenced from the HTML accordingly. 7. All inputs must be properly labeled!

</div>
</div>
</div>
</div>
</div>
