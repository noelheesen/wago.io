<template>
  <div class="document">
    <h1>Privacy Policy</h1>
    <p>At wago.io, we collect and manage user data according to the following Privacy Policy, with the goal of incorporating our company values: transparency, accessibility, sanity, usability. This document is part of wago.io's <router-link to="terms-of-service">Terms of Service</router-link>, and by using wago.io (the “Website”), you agree to the terms of this Privacy Policy and the Terms of Service. Please read the Terms of Service in their entirety, and refer to those for definitions and contacts.</p>
    <p></p>
    <p><strong>Data Collected</strong></p>
    <p>We collect anonymous data from every visitor of the Website to monitor traffic and fix bugs. For example, we collect information like web requests, the data sent in response to such requests, the Internet Protocol address, the browser type, the browser language, and a timestamp for the request.</p>
    <p>We ask you to log in and provide certain personal information (such as a unique username and social media accounts) in order to be able to save your profile and the content and comments associated with it. In order to enable these or any other login based features, we use cookies to store session information for your convenience. You can block or delete cookies and still be able to use wago.io, although if you do you will then be asked for your username and password every time you log in to the Website. </p>
    <p>You are able to view, change and remove your data associated with your profile. Should you choose to delete your account, please contact us at info@wago.io and we will follow up with such request as soon as possible.</p>
    <p>Minors and children should not use wago.io. By using the Website, you represent that you have the legal capacity to enter into a binding agreement.</p>
    <p><strong>Use of the Data</strong></p>
    <p>We only use your personal information to provide you the wago.io services or to communicate with you about the services or the Website.</p>
    <p>We employ industry standard techniques to protect against unauthorized access of data about you that we store, including personal information.</p>
    <p><strong>We do not share personal information you have provided to us without your consent</strong>, unless:</p>
    <ul>
      <li>doing so is appropriate to carry out your own request;</li>
      <li>we believe it's needed to enforce our Terms of Service, or that is legally required;</li>
      <li>we believe it's needed to detect, prevent or address fraud, security or technical issues;</li>
      <li>otherwise protect our property, legal rights, or that of others.</li>
    </ul>
    <p>Wago.io is operated from Canada. If you are visiting the Website from outside Canada, you agree to any processing of any personal information you provide us according to this policy.</p>
    <p>Wago.io will never contact you by email without your express consent.</p>
    <p><strong>Sharing of Data</strong></p>
    <p>We don't share your personal information with third parties. Only aggregated, anonymized data is periodically transmitted to external services to help us improve the wago.io Website and service. We currently use Google Analytics (traffic analysis, SEO optimization). We listed below what data these third parties extract exactly. Feel free to check out their own Privacy Policies to find out more.</p>
    <ul>
      <li>Google Analytics: anonymous (ad serving domains, browser type, demographics, language settings, page views, time/date), pseudonymous (IP address)</li>
    </ul>
    <p>We employ and contract with people and other entities that perform certain tasks on our behalf and who are under our control (our “Agents”). We may need to share personal information with our Agents in order to provide products or services to you. Unless we tell you differently, our Agents do not have any right to use Personal Information or other information we share with them beyond what is necessary to assist us. You hereby consent to our sharing of Personal Information with our Agents.</p>
    <p>We may choose to buy or sell assets. In these types of transactions, user information is typically one of the transferred business assets. Moreover, if we, or substantially all of our assets, were acquired, or if we go out of business or enter bankruptcy, user information would be one of the assets that is transferred or acquired by a third party. You acknowledge that such transfers may occur, and that any acquirer of us or our assets may continue to use your personal information as set forth in this policy.</p>
    <p><strong>Changes to the Privacy Policy</strong></p>
    <p>We may amend this Privacy Policy from time to time. Use of information we collect now is subject to the Privacy Policy in effect at the time such information is used. If we make major changes in the way we collect or use information, we will notify you by posting an announcement on the Website. A user is bound by any changes to the Privacy Policy when he or she uses the Services after such changes have been first posted.</p>
    <p>Should you have any question or concern, please write to info@wago.io.</p>
  </div>
</template>

<script>
export default {
  mounted: function () {
    this.$store.commit('setPageInfo', {
      title: 'Privacy Policy'
    })
  }
}
</script>
