Migrating from version 0.1.3 to 1.0.x
==

The version 1.x is a major change from 0.1.3 and will affect your payments if the migration is not done properly. The advantages of the new plugin are:

  - Easier configuration
  - Better error handling
  - No sensitive data in the URL
  - Faster checkouts
  - Test mode

Currently the configuration page of our plugin looks like this:

![enter image description here](http://i.imgur.com/U0XjleL.png)

After updating to the newer version 1.0.x it will look like:

![enter image description here](http://i.imgur.com/q1aRaa5.png)

----

**Configuring the new version:**

1. **Enable/Disable** - Check this to enable this plugin.
2. **Title** - The plugin name that buyer sees during checkout.
3. **Description** - Additional description related to this checkout method, for example: "Pay using CC/DB/NB and wallets".
4. **Client ID** and **Client Secret** - Client Secret And Client ID can be generated on the [Integrations page](https://www.instamojo.com/integrations/). Related support article: [How Do I Get My Client ID And Client Secret?](https://support.instamojo.com/hc/en-us/articles/212214265-How-do-I-get-my-Client-ID-and-Client-Secret-)
5. **Test Mode** - If enabled you can use our [Sandbox environment](https://support.instamojo.com/hc/en-us/articles/208485675-Test-or-Sandbox-Account) to test payments. Note that in this case you should use Client Secret and Client ID from the test account not production.