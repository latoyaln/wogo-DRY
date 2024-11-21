<script>
    export let items;
  </script>
  
  <section class="reviews-section">
      <article class="review-card">
        <header>
          <h2>{items.title}</h2>
        </header>
        <blockquote>
          <p>"{items.content}"</p>
        </blockquote>
        <footer>
          <span class="rating">⭐ {items.rating}/5</span>
        </footer>
      </article>
  </section>
  
  <style>
    .reviews-section {
      display: grid;
      gap: 2rem;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      padding: 2rem;
      background-color: #f8f8f8;
    }
  
    .review-card {
      background: white;
      border-radius: 0.5rem;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      padding: 1.5rem;
      display: flex;
      flex-direction: column;
      gap: 1rem;
      text-align: left;
      animation: fade-in 1s ease-in-out;
    }
  
    .review-card header {
      border-bottom: 1px solid #eaeaea;
      padding-bottom: 0.5rem;
    }
  
    .review-card h2 {
      font-size: 1.5rem;
      margin: 0;
      font-weight: bold;
      color: #333;
    }
  
    .review-card .reviewer {
      font-size: 0.9rem;
      color: #777;
      margin-top: 0.25rem;
    }
  
    blockquote {
      margin: 0;
      font-size: 1.1rem;
      font-style: italic;
      color: #555;
    }
  
    blockquote p {
      margin: 0;
    }
  
    footer {
      margin-top: auto;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }
  
    .rating {
      font-weight: bold;
      color: #ffb400;
    }
  
    @keyframes fade-in {
      0% {
        opacity: 0;
        transform: translateY(20px);
      }
      100% {
        opacity: 1;
        transform: translateY(0);
      }
    }
  
    @media (min-width: 30em) {
      .reviews-section {
        padding: 3rem;
      }
  
      .review-card {
        padding: 2rem;
      }
    }
  </style>
  