# Lab8-Starter

Alec Fong  
  
GitHub Pages Link: https://smertalec.github.io/Lab8_Starter/  
  
Graceful degradation and Service Workers are related in that we start with "max technology", as in the browser runs with full access to the network, and we "address the lower levels" with Service Workers. Service workers essentially handle the cases where we can't access the network, like when we are offline and without internet. Service Workers store request response pairs in the browser, reducing reliance on the network and gracefully handling the "lower levels".