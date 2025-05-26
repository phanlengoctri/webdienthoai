// CSS styles
<style>
  .khachhang-techzone {
    text-align: center;
    overflow: hidden;
    padding-top: 40px;
  }

  .title-khachhang-techzone {
    font-size: 28px;
    font-weight: bold;
    margin-bottom: 20px;
    position: relative;
    color: #3498db;
    animation: fadeIn 2s ease-in, colorChange 4s linear infinite;
  }

  @keyframes fadeIn {
    from { opacity: 0; }
    to { opacity: 1; }
  }

  @keyframes colorChange {
    0% { color: #3498db; }
    50% { color: #2ecc71; }
    100% { color: #3498db; }
  }
</style>

// React Component
<div className="khachhang-techzone">
  <div className="title-khachhang-techzone">KHÁCH HÀNG CỦA TECHZONE STORE</div>
  <Carousel
    autoPlay
    interval={1500}
    infiniteLoop
    showThumbs={false}
    showArrows
    centerMode
    centerSlidePercentage={33.33}
    showIndicators={false}
    showStatus={false}
  >
    {/* Thêm các <div><img src="..." /></div> tại đây */}
  </Carousel>
</div>
- https://www.tawk.to/
- https://dashboard.render.com/
- npm install express
