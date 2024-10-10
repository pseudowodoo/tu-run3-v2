---
icon: network-wired
---

# Cloudflare

### Creating a Cloudflare account

Follow the instructions in this page below to create your Cloudflare account.

{% embed url="https://developers.cloudflare.com/fundamentals/setup/account/create-account/" %}

### Registering a Domain Name (also known as buying a domain name)

#### 1. Login to Cloudflare Dashboard ([dash.cloudflare.com](https://dash.cloudflare.com/)) and click on Register Domains in the sidebar

<figure><img src="../.gitbook/assets/cf-1.webp" alt=""><figcaption><p>Click on Register Domains to bring you to this page</p></figcaption></figure>

### 2. Type in a domain name of your choice and click purchase

<figure><img src="../.gitbook/assets/cf-2.webp" alt=""><figcaption><p>Enter a domain name and click on purchase</p></figcaption></figure>

#### 3. Select a 1 year registration and fill in your registrant information

<figure><img src="../.gitbook/assets/cf-3.webp" alt=""><figcaption><p>Select 1 year and fill in the registrant information section</p></figcaption></figure>

#### 4. Select the payment method of your choice

<figure><img src="../.gitbook/assets/cf-4.webp" alt=""><figcaption><p>Select your payment method</p></figcaption></figure>

#### 5. Click on Complete Purchase to buy your domain name

<figure><img src="../.gitbook/assets/cf-5.webp" alt=""><figcaption><p>Click on complete purchase</p></figcaption></figure>

#### 6. Congrats you've just purchased your domain name!

<figure><img src="../.gitbook/assets/cf-6.webp" alt=""><figcaption><p>You should see this screen once you have purchased your domain name</p></figcaption></figure>

### Linking my domain name to my web app (using the Sample Web App as an example)

{% hint style="info" %}
You should have already set up your Sample Web App before linking your domain name. If you have yet to do so, please follow the instructions [here](sample-web-app.md).
{% endhint %}

To link your domain name to the sample web app, there are three things you will need to do:

* Enable full SSL/TLS encryption on Cloudflare
* Setup Render to use a custom domain name for your Sample Web App
* Setup Cloudflare's DNS to point to the Sample Web App deployed on Render

#### 1. Go to Cloudflare Dashboard ([dash.cloudflare.com](https://dash.cloudflare.com/)) and click on the domain name you purchased

<figure><img src="../.gitbook/assets/cf-7 (1).webp" alt=""><figcaption><p>Click on your domain name</p></figcaption></figure>

#### 2. Click on the SSL/TLS tab in the sidebar

<figure><img src="../.gitbook/assets/cf-8.avif" alt=""><figcaption><p>Click on the SSL/TLS tab in the sidebar</p></figcaption></figure>

#### 3. Set the SSL/TLS encryption mode to Full

<figure><img src="../.gitbook/assets/cf-9.avif" alt=""><figcaption><p>Select Full to change SSL/TLS encryption mode</p></figcaption></figure>



<figure><img src="../.gitbook/assets/cf-10.avif" alt=""><figcaption><p>Click on Confirm to continue</p></figcaption></figure>

<figure><img src="../.gitbook/assets/cf-11.avif" alt=""><figcaption><p>Your SSL/TLS encryption mode should now be set to full</p></figcaption></figure>

#### 4. Go to Render Dashboard ([dashboard.render.com](https://dashboard.render.com/)) and click on your web app (in this example the sample web app is selected)

<figure><img src="../.gitbook/assets/cf-12.avif" alt=""><figcaption><p>Select your web application on Render</p></figcaption></figure>

#### 5. Click on Settings to Add a Custom Domain Name

<figure><img src="../.gitbook/assets/cf-13.avif" alt=""><figcaption><p>Click on Settings</p></figcaption></figure>

<figure><img src="../.gitbook/assets/cf-17.avif" alt=""><figcaption><p>Scroll down to the section on custom domains</p></figcaption></figure>



<figure><img src="../.gitbook/assets/cf-15.avif" alt=""><figcaption><p>Enter your domain name and click save</p></figcaption></figure>



<figure><img src="../.gitbook/assets/cf-16.avif" alt=""><figcaption><p>You should see something similar, click on the copy icon to copy the onrender.com URL which will be used for the nest step</p></figcaption></figure>

#### 6. Go to Cloudflare Dashboard ([dash.cloudflare.com](https://dash.cloudflare.com/)) and click on your domain name

<figure><img src="../.gitbook/assets/cf-18.avif" alt=""><figcaption><p>Click on your domain name</p></figcaption></figure>

#### 7. Click on DNS to go to the page to edit your DNS Records, then click on Add Record



<figure><img src="../.gitbook/assets/cf-19.avif" alt=""><figcaption><p>Click on DNS in the sidebar then click on Add Record</p></figcaption></figure>

#### 8. Add a new DNS Record

<figure><img src="../.gitbook/assets/cf-20.avif" alt=""><figcaption><p>Add a new CNAME record with the Target being the onrender.com URL you copied earlier in Step 5, then click Save</p></figcaption></figure>

#### 9. Go back to your Render Dashboard and click on Verify

<figure><img src="../.gitbook/assets/cf-21.avif" alt=""><figcaption><p>Click on Verify</p></figcaption></figure>

<figure><img src="../.gitbook/assets/cf-22.avif" alt=""><figcaption><p>It may take some time for the domain to be verified and for a certificate to be automatically generated</p></figcaption></figure>

<figure><img src="../.gitbook/assets/cf-23.avif" alt=""><figcaption><p>Congrats! You have now set up a custom domain name for your app!</p></figcaption></figure>
