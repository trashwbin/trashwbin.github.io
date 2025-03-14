---
title: "让我们聊聊"
draft: false
---

<div class="contact-message">
我正在与来自不同领域的人们合作，这正是我创建这个网站的原因。
<span class="highlight-text">随时欢迎与我联系</span>
</div>

<div class="contact-methods">
  <a href="mailto:Trashwbin@gmail.com" class="contact-link">
    <span class="contact-icon">📧</span>
    <span class="contact-email">Trashwbin@gmail.com</span>
  </a>
</div>

<div class="contact-footer">
  <p>✨ 热爱开源，期待有朝一日能启动自己的项目</p>
  <p>🤝 对合作充满热情，让我们一起创造有趣的项目！</p>
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
  transition: transform 0.2s ease;
}

.contact-link:hover {
  transform: translateY(-2px);
}

.contact-icon {
  font-size: 1.5rem;
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

