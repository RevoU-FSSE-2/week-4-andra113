# README: Buying Domain at Niaga Hoster and Deploying to Netlify with Custom Domain using Cloudflare

Hey there! 👋🏻 I'm Andra, and I created this README to submit my assignment for RevoU.

This documentation will guide you through the process of purchasing a domain from Niaga Hoster, deploying your website to Netlify using a custom domain, and configuring DNS settings using Cloudflare. By following these steps, you'll be able to register your domain, set up your website, and manage DNS records for your domain.

## Prerequisites

Before you get started, make sure you have the following:

- A computer with internet access
- An account on Niaga Hoster ([https://www.niagahoster.co.id/](https://www.niagahoster.co.id/))
- An account on Netlify ([https://www.netlify.com/](https://www.netlify.com/))
- An account on Cloudflare ([https://www.cloudflare.com/](https://www.cloudflare.com/))

## Steps

### 1. Purchase a Domain from Niaga Hoster

1. Go to the Niaga Hoster website ([https://www.niagahoster.co.id/](https://www.niagahoster.co.id/)) and log in to your account.

2. Search for an available domain name using the provided search bar.

   ![Search for domain](path/to/search_domain.png)

3. Select the desired domain from the search results and proceed to the checkout page.

   ![Select domain](path/to/select_domain.png)

4. Follow the on-screen instructions to complete the domain registration process, providing the necessary information and making the payment.

   ![Complete registration](path/to/complete_registration.png)

### 2. Deploy Website to Netlify

1. Log in to your Netlify account.

2. On the Netlify dashboard, click on "New site from Git."

   ![New site from Git](path/to/new_site_from_git.png)

3. Connect your Git repository or drag and drop your website files to the designated area.

   ![Connect repository](path/to/connect_repository.png)

4. Configure the build settings according to your project requirements.

   ![Configure build settings](path/to/configure_build_settings.png)

5. Once the build configuration is complete, your website is deployed on Netlify.

   ![Deploy site](path/to/deploy_site.png)

### 3. Set up Custom Domain in Netlify

1. After the deployment is complete, click on the "Site settings" button for your deployed site.

2. In the settings menu, navigate to "Domain management."

   ![Domain management](path/to/domain_management.png)

3. In the "Custom domains" section, click on "Add custom domain."

   ![Add custom domain](path/to/add_custom_domain.png)

4. Enter your purchased domain from Niaga Hoster (e.g., `yourdomain.com`) and click "Save."

   ![Enter custom domain](path/to/enter_custom_domain.png)

5. Netlify will provide you with DNS configuration instructions. Make sure to note them down for the next step.

   ![DNS configuration](path/to/dns_configuration.png)

### 4. Configure DNS using Cloudflare

1. Log in to your Cloudflare account.

2. On the Cloudflare dashboard, click on "Add a site" to add your domain.

   ![Add a site](path/to/add_a_site.png)

3. Enter your domain name (e.g., `yourdomain.com`) and click on "Add site."

   ![Enter domain name](path/to/enter_domain_name.png)

4. Cloudflare will scan your DNS records. Once the scan is complete, click on "Next."

   ![DNS scan](path/to/dns_scan.png)

5. Review the DNS records found by Cloudflare. Make any necessary changes and click on "Continue."

   ![Review DNS records](path/to/review_dns_records.png)

6. Choose the free plan or the desired plan level, and click on "Confirm plan."

   ![Choose plan](path/to/choose_plan.png)

7. Cloudflare will provide you with two nameservers. Take note of them.

   ![Nameservers](path/to/nameservers.png)

8. Go to your Niaga Hoster account and find the DNS management or nameserver configuration section.

   ![DNS management](path/to/dns_management.png)

9. Replace the existing nameservers with the ones provided by Cloudflare and save the changes.

   ![Replace nameservers](path/to/replace_nameservers.png)

### 5. Verify and Finalize

1. Return to your Netlify account and navigate to the "Domain management" section for your site.

2. Click on "Verify DNS configuration."

   ![Verify DNS configuration](path/to/verify_dns_configuration.png)

3. Netlify will perform a DNS lookup to verify the changes.

4. Once the DNS configuration is verified, click on "Set up SSL" to enable HTTPS for your domain.

   ![Set up SSL](path/to/set_up_ssl.png)

5. Netlify will automatically provision an SSL certificate for your domain.

6. Wait for the SSL certificate provisioning process to complete.

7. Congratulations! Your website should now be live and accessible through your custom domain.

That's it! You've successfully purchased a domain from Niaga Hoster, deployed your website to Netlify with a custom domain, and configured DNS settings using Cloudflare. Enjoy your new website! 🚀
