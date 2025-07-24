---
title: "Book A Consult"
layout: "simple"
---


<form
  action="https://formspree.io/f/mgvzazed"
  class="fs-form"
  target="_top"
  method="POST"
>
  <fieldset>
    <legend class="fs-fieldset-title">Contact Information</legend>
    <div class="fs-field">
      <label class="fs-label" for="full-name">Full Name</label>
      <input
        class="fs-input"
        id="full-name"
        name="full-name"
        placeholder="Enter your full name"
        required
      />
    </div>
    <div class="fs-field">
      <label class="fs-label" for="email-address">Email Address</label>
      <input
        class="fs-input"
        id="email-address"
        name="email-address"
        placeholder="Enter your email address"
        required
      />
    </div>
  </fieldset>
  <fieldset>
    <legend class="fs-fieldset-title">Support Request Details</legend>
    <div class="fs-field">
      <label class="fs-label" for="support-type">Type of Support Needed</label>
      <select class="fs-select" id="support-type" name="support-type" required>
        <option value="technical-issue">Technical Issue</option>
        <option value="cassette-digitization">Cassette Digitization</option>
        <option value="virus-removal">Virus Removal</option>
        <option value="general-question">General Question</option>
      </select>
    </div>
    <div class="fs-field">
      <label class="fs-label" for="subject-of-request">
        Subject of Request
      </label>
      <input
        class="fs-input"
        id="subject-of-request"
        name="subject-of-request"
        placeholder="Enter the subject of your request"
        required
      />
    </div>
    <div class="fs-field col-span-full">
      <label class="fs-label" for="detailed-description">
        Detailed Description of the Issue or Request
      </label>
      <textarea
        class="fs-textarea"
        id="detailed-description"
        name="detailed-description"
        placeholder="Provide a detailed description"
        required
      ></textarea>
    </div>
    <div class="fs-field">
      <label class="fs-label" for="product-or-service">
        Product or Service Related To
      </label>
      <input
        class="fs-input"
        id="product-or-service"
        name="product-or-service"
        placeholder="Enter the related product or service"
      />
    </div>
    <div class="fs-field">
      <label class="fs-label" for="attachment">
        Optional Attachment (Screenshots, Error Logs, etc.)
      </label>
      <input
        class="fs-input"
        id="attachment"
        name="attachment"
        placeholder="Add a link after uploading files to Google Drive, Dropbox, etc."
      />
    </div>
    <div class="fs-field">
      <label class="fs-label" for="device-browser-info">
        Device / Browser Information (if applicable)
      </label>
      <input
        class="fs-input"
        id="device-browser-info"
        name="device-browser-info"
        placeholder="e.g., iPhone 14, Chrome"
      />
    </div>
    <div class="fs-field">
      <label class="fs-label" for="best-time-to-reach">
        Best Time to Reach You (optional)
      </label>
      <input
        class="fs-input"
        id="best-time-to-reach"
        name="best-time-to-reach"
        placeholder="e.g., Weekdays 2-5 PM"
      />
    </div>
    <div class="fs-button-group">
      <button class="fs-button" type="submit">Submit</button>
    </div>
  </fieldset>
</form>
