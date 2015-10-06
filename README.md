# Responsive-Bootstrap
eBay Item search using Bootstrap,JQuery, and Facebook Mashup
In this project, I created a webpage that allows users to search for items on eBay.com using the eBay Api and the reulstfrom the search are displayed in a list format on the same page below the form. In order to do this I created a PHP file to return JSON formatted data to the front end by making asynchronous AJAX call and the front end will parse the JSON data and display it using Bootstrap Javascript.Once the user provides data in the form and clicks the Search button validation is done to check if the data entered is valid. Once this validation is successful , the jQuery function.ajax() is executed to start an asynchronous transaction with a PHP script running on AWS server and passing the search form data as parameters of the transaction.The JSON output from the PHP file  has all the necessary data and links to generate the front end information.The search form is responsive to devices like a smart phone or a tablet depending on the width of the devices. The successful display of results includes the mention of the range of items from total number of items. The list of items are vertically stacked using Bootstrap Media Object.In addition , on clicking the image of an item , a modal dialog is displayed with the maginified size picture of the item. The purchase of a particular item can be posted on Facebook.Below the list of results a pagination bar is displayed where in you can scroll through the pages to jump to a specific page
