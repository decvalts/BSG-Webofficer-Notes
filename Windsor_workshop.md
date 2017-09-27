# Windsor workshop

The Windsor workshop runs every year in December and bookings generally open around September time. There is a designated contact who coordinates the bookings and runs the workshop. Generally this person should be given Site Admin priveleges so they are able to update the relevant text on the site, add photos, and view bookings.

## Windsor workshop page

This is linked from the main menu under 'Postgraduates'. The page is a custom Drupal content type called "Windsor Workshop". You don't need to create a new instance of it every year, just edit the exisiting page under the Admin panel via `Content` and then filter by type `Windsor Workshop` to find the link to editing the page. (Alternatively just visit the page and click the 'Edit' tab.)

Text can be edited using the standard editor box. Pictures can be uploaded using the widget at the bottom when in Edit view.

### Activating bookings
When you or the Windsor Workshop Officer are ready, open the page in Edit mode and click the radio button that says 'Active' under 'Accept Bookings'. Once this is done an 'Apply' button will become visible at the top of the page after saving the changes.

**Note: This apply button is only visible to users with the Postgraduate membership type.** You will not see it even as a Site Admin (unless you also happen to be a postgrad), but you can check using the Postagrad Test Account.

## Windsor workshop (product)

A Drupal module called `ubercart` is used to manage the pricing and checkout of the bookings. To edit the pricing of the Workshop Booking, from the Admin Panel, go to `Store > Products` and the click 'Booking for Windsor Workshop' under the list of ubercart products. Click edit to be able to change the price. All of the price boxes (List Price, Sell Price, etc.) should be set to the same value. The product should be marked as 'Shippable' to enable us to collect attendees' addresses.

### Managing stock levels

You can set how many products (Here: bookings) are available to purchase via the 'Stock' widget. This accessed by clicking the 'Stock' button that appears in the top right hand corner when you are viewing the Windsor Workshop (product) in Edit mode. You can set the total stock level and a threshold level, which is used to notify an email address when this threshold is reached.

**Note:** There is a known limitation in the ubercart product system that currently allows you to go below the minimum stock level and still carry on selling the product! I.e. once stock has reached zero, it will still be available to purchase. Use the email notification to manually keep track of stock levels and manually disable workshop bookings when a critical level has been reached.

### Email stock notification

To keep track of bookings/stock remaining, you can set up email notifications by going to (from the admin panel): `Store > Configuration > Stock notifications` and changing the email address in the page that appears in the first box on this link. This email address when the stock reaches the threshold set above.

## Viewing and Managing Orders

The Windsor Workshop Officer (or any Site Admin) can manage orders when logged in to the site by going to `BSG Admin > Windsor Bookings`. Contact details for each order can be found by clicking on the order number next to the name of the attendee.

Note: Full admins can also go to `Store > Orders > View orders`, but it is much the same as the other link.

### Windsor Workshop Bookings

A note here just to say that there is a custom Drupal content type called 'Windsor Workshop Booking', which is created for every booking made. It is not to be confused with the content type 'Windsor Workshop' which is the actual page itself advertising the course.
