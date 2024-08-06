<svg fill="none" viewBox="0 0 600 120" width="600" height="120" xmlns="http://www.w3.org/2000/svg">
  <foreignObject width="100%" height="100%">
    <div xmlns="http://www.w3.org/1999/xhtml">
      <style>
        @keyframes type {
          0% { width: 0ch; }
          25% { width: 12ch; }
          50% { width: 12ch; }
          75% { width: 0ch; }
          100% { width: 0ch; }
        }
        @keyframes blink {
          0% { opacity: 0; }
          50% { opacity: 1; }
          100% { opacity: 0; }
        }
        .container {
          width: 600px;
          height: 120px;
          background-color: #20232A;
          display: flex;
          justify-content: flex-start;
          align-items: center;
          padding-left: 20px;
        }
        .text {
          color: #fff;
          font-family: Arial, sans-serif;
          font-size: 36px;
          white-space: nowrap;
          overflow: hidden;
          border-right: 3px solid #fff;
          animation: type 8s steps(12) infinite, blink 0.5s step-end infinite alternate;
        }
      </style>
      <div class="container">
        <div class="text">Hello World!</div>
      </div>
    </div>
  </foreignObject>
</svg>
