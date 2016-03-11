---
layout: post
title: TaylorMade Golf PreOwned
excerpt: HTML Email development, prototyping, and branding projects for TaylorMade PreOwned.
permalink: /taylormade-preowned/
bg: "#f4aa00;
background: -webkit-linear-gradient(to right, #ffc430, #f4aa00);
background: linear-gradient(to right, #ffc430, #f4aa00);"
---
<section>
    <figure class="overlap">
        <img src="/images/taylormade-preowned/laptop-mockup.png" alt="C1 Marketing Group Website" />
    </figure>
    
    
    <p><strong>TaylorMade PreOwned</strong> is a <a href="http://globalvaluecommerce.com">Global Value Commerce</a> site that is a result of our great relationship with <a href="http://taylormadegolf.com/">TaylorMade</a> and our commitment to providing quality preowned equipment. From the color palette to the typeface this has been one of my favorite sites to take visual ownership of. I get to work on a wide-range of things for the site including homepage concepts and css animation prototyping. Here are some of my favorite emails, illustrations & animations since I joined the GVC team in 2012.</p>

    <h4 class="light-grey">Role: HTML Email Development, Design, Prototyping</h4>
</section>

<section>
    <h2>Responsive HTML Email Template</h2>
    <p>It is no secret that email is a huge marketing tool for e-commerce and drives more traffic and conversion than nearly any other option. Since we have seen mobile email traffic jump from 25% to over half in the last couple years we decided to create responsive versions of all our email templates. I was tasked with creating a responsive version of our existing templates. In these new templates we simplified the navigation and added an HTML text Call to Action button that works when images are turned off.</p>
    <div class="row divider">
        <div class="half">
             <h3>Before</h3>
            <img src="/images/taylormade-preowned/email-before.png" alt="C1 Marketing Group Logo" />
        </div>
        <div class="half">
            <h3>After</h3>
            <img src="/images/taylormade-preowned/email-after.png" alt="C1 Marketing Group Logo" />
        </div>
    </div>
    <h3>Mobile Navigation</h3>
    <p>After an of A/B test of text abbreviations vs icons we decided to move forward with icons for the main mobile navigation. Displaying and hiding elements in an email can be rather tricky since neither Gmail or Outlook support the <code>display</code>, <code>visibility</code>, or <code>opacity</code> properties. To implement this responsive technique we developed a clever workaround that uses a media-query to display the icons as a <code>background-image</code> in the outer <code>td</code> while hiding the inner text. Since Gmail and Outlook also do not support <code>@media</code> it allowed us to give a friendly mobile experience to progressive email clients and a clean text-only navigation to the rest.</p>
    <p>
        <img src="/images/taylormade-preowned/tmpo-mobile-email.png" alt="C1 Marketing Group Logo" />
    </p>
</section>
<section>
    <div class="row centered">
        <div class="half">
             <h2>Prototyping</h2>
             <p>When we began moving forward with updating the mobile header I built working prototypes of a mobile navigation that mimicked the colors of our desktop navigation. The animations were done with CSS but didn&rsquo;t make the final handoff since certain android devices rendered in a very jarring manner.</p>
             <p>It was fun doing some research and finding out some CSS elements, like <code>line-height</code>, have a smaller effect on repaints than animating heavier elements such as <code>height</code>.</p>
        </div>
        <div class="half">
            <video id="tmpo-nav" autoplay loop>
              <source src="/images/taylormade-preowned/tmpo-mobile-nav2.mp4" type="video/mp4">
              Your browser does not support the video tag.
            </video>
        </div>
    </div>
</section>
<section>
    <div class="row centered">
        <div class="half">
            <img src="/images/taylormade-preowned/30day-follow-through.svg" alt="30 Day Follow Through Logo" />
        </div>
        <div class="half">
             <h2>Internal Branding</h2>
             <p>We were introducing a new purchase guarantee to give us an edge against brick and mortar stores. The badge/logo needed to stay within current brand guidelines (typography and color palette), mesh with existing site badges and demonstrate visual elements of a golf swing follow-through.</p>
        </div>
    </div>
</section>
<section>
    <h2>Interface Inventory</h2>
    <p>Working in a larger e-commerce company, opportunities for full redesigns are very difficult. However steps can be taken to keep the majority of the current layout and make improvements through an audit of the site&rsquo;s typography and UI elements to make a more consistent and user friendly experience.</p>
    <p>The focus of this audit was to create better page hierarchy through consistent typography and type color. Next we A/B tested different image sizes and whitespace for better conversion on product pages. Finally we created a cleaner mobile header, updated the shopping cart icon to better fit within the branding and consolidated the product filter to allow more content to be pulled into the screen.</p>
    
    <p><a class="visit" href="http://www.taylormadegolfpreowned.com/">Visit the site</a></p>
    <div class="row divider"></div>
    <div class="row divider">
        <div class="half">
             <h3>Gallery View Before</h3>
             <p><img src="/images/taylormade-preowned/gallery-before.gif" alt="30 Day Follow Through Logo" /></p>
        </div>
        <div class="half">
            <h3>Gallery View After</h3>
            <p><img src="/images/taylormade-preowned/gallery-after.gif" alt="30 Day Follow Through Logo" /></p>
        </div>
    </div>
    
    <div class="row divider">
        <div class="half">
             <h3>Product Page Before</h3>
             <p><img src="/images/taylormade-preowned/product-before.gif" alt="30 Day Follow Through Logo" /></p>
        </div>
        <div class="half">
            <h3>Product Page After</h3>
            <p><img src="/images/taylormade-preowned/product-after.gif" alt="30 Day Follow Through Logo" /></p>
        </div>
    </div>
    <div class="row divider">
        <div class="half">
             <h3>Mobile Header/Filter Before</h3>
             <p><img src="/images/taylormade-preowned/mobile-before.gif" alt="30 Day Follow Through Logo" /></p>
        </div>
        <div class="half">
            <h3>Mobile Header/Filter After</h3>
            <p><img src="/images/taylormade-preowned/mobile-after.gif" alt="30 Day Follow Through Logo" /></p>
        </div>
    </div>
    <p>This process was very tedious but when those small changes populate throughout the site they really add up. The result was a great improvement in the user experience and site conversion with mimimal effort needed for developers to implement.</p>
</section>
<section class="next" onclick="location.href='/rocky-mount-radiator/';">
    <h2>Next, read about <a href="/rocky-mount-radiator/">Rocky&nbsp;Mount&nbsp;Radiator</a></h2>
</section>