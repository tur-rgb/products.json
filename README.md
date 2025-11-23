const url = "https://raw.githubusercontent.com/tur-rgb/nama-repo/main/products.json";

fetch(url)
  .then(response => response.json())
  .then(data => {
    console.log(data); // Data siap digunakan!
    // Lakukan sesuatu dengan data, misal tampilkan di HTML
  })
  .catch(error => console.error('Error:', error));
