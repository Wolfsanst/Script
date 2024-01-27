.star-animation {
  width: 100%;
  height: 100%;
  background-image: linear-gradient(to bottom, rgba(255, 255, 255, 0.5), rgba(255, 255, 255, 0.5)), url("startransparent.gif"), url("catfront.png");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  animation: star-animation 5s infinite linear;
}

@keyframes star-animation {
  0% {
    background-position: center;
  }
  50% {
    background-position: 100% 100%;
  }
  100% {
    background-position: center;
  }
}
