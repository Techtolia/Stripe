# Accept payments with Stripe in ASP.NET & C# - ASP.NET Web Forms || ASP.NET Core MVC

## Demo: https://techtolia.com/Stripe/

The application, ASP.NET Web Forms or Core MVC Web Application builded for Stripe Checkout custom payment forms on the web.

With integrating and customizing the application to your ASP.NET Web Application, receive payments from credit or debit cards, Alipay, WeChat Pay, Bancontact, EPS, giropay, iDEAL, Multibanco, Przelewy24, SOFORT, Secure Remote Commerce and Payment Request Button (Apple Pay, Google Pay, Microsoft Pay, and the browser Payment Request API) via Stripe.

The application supports 3D Secure 2 for card payments. Supported Card Brands: Visa - Mastercard - American Express - Discover - Dinners Club - JCB - UnionPay

Before use a Payment Method in Live Mode, it must be activated on the Stripe Dashboard, no need in Test Mode. Supported Payment Methods:

* Alipay (AUD, CAD, EUR, GBP, HKD, JPY, NZD, SGD, USD)

* WeChat Pay (AUD, CAD, EUR, GBP, HKD, JPY, NZD, SGD, USD)

* Bancontact (EUR): Belgium

* EPS (EUR): Austria

* giropay (EUR): Germany

* iDEAL (EUR): Netherlands

* Multibanco (EUR): Portugal

* Przelewy24 (EUR, PLN): Poland

* SOFORT (EUR): Germany, Austria, Belgium, Spain, Italy, Netherlands

Elements are completely customizable. You can style Elements to match the look and feel of your site, providing a seamless checkout experience for your customers.

The application uses:

- the Payment Intents API for cards

- the Sources API for Alipay, WeChat Pay, Bancontact, EPS, giropay, iDEAL, Multibanco, Przelewy24 and SOFORT

Full source code is included.

-- ASP.NET Web Forms -- Target Framework: .NET Framework 4.7.2 - Language: c#

-- ASP.NET Core MVC -- Target Framework: .NET Core – ASP.NET Core 3.1 – Language: c#


### What is Payment Request Button?
Collect payment and address information from customers who use Apple Pay, Google Pay, Microsoft Pay, and the browser Payment Request API (Chrome, Opera, Edge, Safari).

Customers see a “Pay now” button or an Apple Pay button, depending on what their device and browser combination supports. If neither option is available, they don’t see the button. Supporting Apple Pay requires additional steps, but compatible devices automatically support browser-saved cards, Google Pay, and Microsoft Pay.


### What is Secure Remote Commerce? (New)
Goodbye to Amex Express Checkout, Masterpass and Visa Checkout. Those online payment setups are going away.

American Express, Discover, Mastercard and Visa — rolled out Secure Remote Commerce. It’s designed to simplify the online checkout process and further secure your personal information, whether it’s associated with a credit, debit or prepaid card.

Secure Remote Commerce (SRC) is an easy and secure way to pay online and is powered by the global payments industry to protect users’ payment information. Users can add cards from participating networks and enable click to pay simply and securely. Secure Remote Commerce delivers an enhanced online checkout experience and supports all network brands participating in SRC.

SRC is only available to US merchants.

### What is Strong Customer Authentication?
Strong Customer Authentication (SCA) is a new European regulatory requirement to reduce fraud and make online payments more secure. To accept payments and meet SCA requirements, you need to build additional authentication into your checkout flow.

Banks will need to start declining payments that require SCA and don’t meet these criteria. Although the regulation was introduced on 14 September 2019, we expect these requirements to be enforced by regulators over the course of 2020 and 2021.

3D Secure 2—the new version of the authentication protocol rolling out in 2019—will be the main method for authenticating online card payments and meeting the new SCA requirements. This new version introduces a better user experience that will help minimise some of the friction that authentication adds into the checkout flow.

The application supports 3D Secure 2

The Payment Intents API that uses Stripe’s SCA logic to apply the right exemption and trigger 3D Secure when necessary.

The application uses the Payment Intents API for card payments
