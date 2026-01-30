<style>
.news-scroll-container {
  max-height: 260px; /* 可根据需要调整 */
  overflow-y: auto;
  padding: 12px;
  border: 1px solid #e0e0e0;
  border-radius: 8px;
  background-color: #ffffff; /* 更新为白色背景 */
  margin: 1rem 0;
}

/* 美化滚动条（仅 WebKit 浏览器，如 Chrome/Safari） */
.news-scroll-container::-webkit-scrollbar {
  width: 6px;
}
.news-scroll-container::-webkit-scrollbar-track {
  background: #f1f1f1;
  border-radius: 3px;
}
.news-scroll-container::-webkit-scrollbar-thumb {
  background: #b0b0b0;
  border-radius: 3px;
}
.news-scroll-container::-webkit-scrollbar-thumb:hover {
  background: #909090;
}

.news-item {
  margin-bottom: 8px; /* 缩小了间距，从12px改为8px */
  line-height: 1.4; /* 调整行高，使文字更紧凑 */
  font-size: 0.95em;
  position: relative; /* 为项目符号定位做准备 */
}

.news-item:last-child {
  margin-bottom: 0; /* 移除最后一个项目的底部边距 */
}

.news-item::before {
  content: "- "; /* 添加项目符号 */
  position: absolute;
  left: 0;
  top: 0;
  color: #2c3e50; /* 与日期颜色一致 */
  font-weight: bold;
}

.news-item-content {
  margin-left: 16px; /* 为项目符号留出空间 */
}

.news-date {
  font-weight: bold;
  color: #2c3e50;
}

.venue {
  font-weight: bold;
  color: #3498db; /* 更新为蓝色 */
}
</style>

<div class="news-scroll-container">
  <div class="news-item"><span class="news-item-content"><span class="news-date">[January 2026]</span> Our paper is accepted to <span class="venue">ICLR 2026</span>.</span></div>
  <div class="news-item"><span class="news-item-content"><span class="news-date">[January 2026]</span> Our paper is accepted to <span class="venue">TOMM</span>.</span></div>
  <div class="news-item"><span class="news-item-content"><span class="news-date">[December 2025]</span> Our paper about incremental learning is accepted to <span class="venue">TIP</span>.</span></div>
  <div class="news-item"><span class="news-item-content"><span class="news-date">[November 2025]</span> Two papers are accepted to <span class="venue">AAAI 2026</span>.</span></div>
  <div class="news-item"><span class="news-item-content"><span class="news-date">[July 2025]</span> Our paper about incremental learning is accepted to <span class="venue">TOMM</span>.</span></div>
  <div class="news-item"><span class="news-item-content"><span class="news-date">[June 2025]</span> Our paper about incremental learning is accepted to <span class="venue">JIG 2025</span>.</span></div>
  <div class="news-item"><span class="news-item-content"><span class="news-date">[June 2025]</span> Three papers are accepted to <span class="venue">ICCV 2025</span>.</span></div>
  <div class="news-item"><span class="news-item-content"><span class="news-date">[May 2025]</span> Our paper about incremental learning is accepted to <span class="venue">TCSVT</span>.</span></div>
  <div class="news-item"><span class="news-item-content"><span class="news-date">[May 2025]</span> Our paper about diffusion models is accepted to <span class="venue">ICML 2025</span>.</span></div>
  <div class="news-item"><span class="news-item-content"><span class="news-date">[April 2025]</span> Two papers are accepted to <span class="venue">IJCAI 2025</span>.</span></div>
</div>



