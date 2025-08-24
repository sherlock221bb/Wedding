body {
  margin: 0;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  color: #333;
  background: #fff;
}

h1, h2 {
  font-family: 'Brush Script MT', cursive;
  color: #d4af37; /* Gold */
}

.hero {
  position: relative;
  height: 100vh;
  background: url('images/photo1.jpg') no-repeat center center/cover;
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
  text-align: center;
}

.hero .overlay {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: rgba(0,0,0,0.4);
}

.hero-content {
  position: relative;
  z-index: 2;
}

#countdown {
  font-size: 1.5em;
  margin-top: 10px;
}

.details, .schedule, .gallery, .rsvp {
  padding: 50px 20px;
  text-align: center;
}

.schedule ul {
  list-style: none;
  padding: 0;
}

.schedule li {
  margin: 10px 0;
}

.gallery-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

.gallery-grid img {
  width: 100%;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.2);
}

.rsvp-btn {
  display: inline-block;
  padding: 15px 30px;
  background: #d4af37;
  color: white;
  text-decoration: none;
  border-radius: 30px;
  font-size: 1.2em;
  transition: 0.3s;
}

.rsvp-btn:hover {
  background: #b9962d;
}

footer {
  background: #f8f8f8;
  padding: 20px;
  text-align: center;
  font-size: 0.9em;
}
