---
title: "Let's Chat"
draft: false
---

<div class="contact-message">
I'm collaborating with individuals from diverse fields, which is precisely why I created this website.
<span class="highlight-text">Feel free to contact me.</span>
</div>

<div class="contact-methods">
  <a href="mailto:Trashwbin@gmail.com" class="contact-link">
    <svg class="contact-icon" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
      <path d="M3 8L10.89 13.26C11.2187 13.4793 11.6049 13.5963 12 13.5963C12.3951 13.5963 12.7813 13.4793 13.11 13.26L21 8M5 19H19C19.5304 19 20.0391 18.7893 20.4142 18.4142C20.7893 18.0391 21 17.5304 21 17V7C21 6.46957 20.7893 5.96086 20.4142 5.58579C20.0391 5.21071 19.5304 5 19 5H5C4.46957 5 3.96086 5.21071 3.58579 5.58579C3.21071 5.96086 3 6.46957 3 7V17C3 17.5304 3.21071 18.0391 3.58579 18.4142C3.96086 18.7893 4.46957 19 5 19Z" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
    </svg>
    <span class="contact-email">Trashwbin@gmail.com</span>
  </a>
</div>

<div class="contact-footer">
  <p>✨ Love open source and looking forward to starting my own projects</p>
  <p>🤝 Passionate about collaboration, let's create something interesting together!</p>
</div>

<style>
.contact-message {
  font-size: 1.5rem;
  line-height: 1.5;
  margin-bottom: 3rem;
  max-width: 800px;
  margin-left: auto;
  margin-right: auto;
  padding: 0 1rem;
}

@media (min-width: 768px) {
  .contact-message {
    font-size: 2rem;
  }
}

.highlight-text {
  position: relative;
  display: inline-block;
  padding: 0.25rem 0.5rem;
  margin: 0 0.25rem;
  border-radius: 0.5rem;
  background: linear-gradient(to right, #f39c12, #e74c3c);
  color: white;
  font-weight: 500;
}

.contact-methods {
  display: flex;
  justify-content: center;
  margin: 3rem auto;
  text-align: center;
}

.contact-link {
  display: inline-flex;
  align-items: center;
  gap: 0.75rem;
  padding: 0.75rem 1.5rem;
  text-decoration: none;
  color: #2c3e50;
  transition: all 0.3s ease;
}

.contact-link:hover {
  transform: translateY(-2px);
  color: #f39c12;
}

.contact-icon {
  width: 1.75rem;
  height: 1.75rem;
  transition: transform 0.3s ease;
}

.contact-link:hover .contact-icon {
  transform: scale(1.1);
}

.contact-email {
  font-size: 1.2rem;
  font-weight: 500;
}

.contact-footer {
  margin-top: 3rem;
  text-align: center;
  color: #666;
  line-height: 1.8;
}

.contact-footer p {
  margin: 0.5rem 0;
}

@media (max-width: 480px) {
  .contact-email {
    font-size: 1rem;
  }
}
</style>

