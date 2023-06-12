<template>
  <div id="page-container">
    <div class="main-section">
      <div class="left-bg"></div>
      <div class="right-bg"></div>
      <div class="main-row">
        <div class="left-col">
          <div class="phone">
            <div class="speaker"></div>
            <div class="chat-header">
              <div class="chat-back"></div>
              <div class="person-image">
                <img src="./assets/avatar.jpg" alt="avatar" />
              </div>
              <div class="person-info">
                <div class="person-name">Samuel Green</div>
                <div class="person-status">Available to Walk</div>
              </div>
              <div class="chat-settings">
                <div class="dot"></div>
                <div class="dot"></div>
                <div class="dot"></div>
              </div>
            </div>
            <div class="chat-body">
              <div class="chat-block">
                <div class="sender-message">
                  That sounds great. I’d be happy with that.
                </div>
                <div class="sender-message">
                  Could you send over some pictures of your dog, please?
                </div>
              </div>
              <div class="chat-block">
                <div class="my-images">
                  <img src="./assets/dog-image-1.jpg" alt="dog image" />
                  <img src="./assets/dog-image-2.jpg" alt="dog image" />
                  <img src="./assets/dog-image-3.jpg" alt="dog image" />
                </div>
                <div class="my-message">
                  Here are a few pictures. She’s a happy girl!
                </div>
                <div class="my-message">Can you make it?</div>
              </div>
              <div class="chat-block">
                <div class="sender-message">
                  She looks so happy! The time we discussed works. How long
                  shall I take her out for?
                </div>
                <div class="sender-service">
                  <div class="service-check"></div>
                  <div class="service-message">30 minute walk</div>
                  <div class="service-price">$29</div>
                </div>
                <div class="sender-service">
                  <div class="service-check"></div>
                  <div class="service-message">1 hour walk</div>
                  <div class="service-price">$49</div>
                </div>
              </div>
            </div>
            <div class="chat-input">
              <form action="javascript:void(0);">
                <input
                  type="text"
                  name="message"
                  id="message"
                  placeholder="Type a message..."
                />
                <button id="submit" type="submit">
                  <div class="arrow"></div>
                </button>
              </form>
            </div>
          </div>
        </div>
        <div class="right-col">
          <h1>Simple booking</h1>
          <p>
            Stay in touch with our dog walkers through the chat interface. This
            makes it easy to discuss arrangements and make bookings. Once the
            walk has been completed you can rate your walker and book again all
            through the chat.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>
