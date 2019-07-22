+++
data = "2019"
title = "Get In Touch"
+++

<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.0/css/bootstrap.min.css">
<div class="inner contact">
    <!-- Form Area -->
    <div class="contact-form">
        <!-- Form -->
        <form id="contact-us" method="post" action="/thankyou" name="Contact" data-netlify="true" netlify-honeypot="bot-field" netlify>
            <!-- Left Inputs -->
            <div class="col-xs-6 wow animated slideInLeft" data-wow-delay=".5s">
                <!-- Name -->
                <input type="text" name="name" id="name" required="required" class="form" placeholder="Name" />
                <!-- Email -->
                <input type="email" name="mail" id="mail" required="required" class="form" placeholder="Email" />
                <!-- Subject -->
                <input type="text" name="subject" id="subject" required="required" class="form" placeholder="Subject" />
            </div><!-- End Left Inputs -->
            <!-- Right Inputs -->
            <div class="col-xs-6 wow animated slideInRight" data-wow-delay=".5s">
                <!-- Message -->
                <textarea name="message" id="message" class="form textarea"  placeholder="Message"></textarea>
            </div><!-- End Right Inputs -->
            
            <div class="relative fullwidth col-xs-12" data-netlify-recaptcha></div>

            <!-- Bottom Submit -->
            <div class="relative fullwidth col-xs-12">
                <!-- Send Button -->
                <button type="submit" id="submit" name="submit" class="form-btn semibold">Send Message</button> 
            </div><!-- End Bottom Submit -->
            <!-- Clear -->
            <div class="clear"></div>
        </form>
    </div>
</div>
