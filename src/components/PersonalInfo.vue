<template>
    <div class="flex items-center justify-center min-h-screen bg-gray-100">
      <div class="bg-white shadow-lg rounded-2xl p-6 max-w-sm text-center">
        <h1 class="text-2xl font-bold text-gray-800">Datos Personales</h1>
        <div class="mt-4 text-gray-600">
          <p><strong>Nombre:</strong> {{ name }}</p>
          <p><strong>Edad:</strong> {{ age }}</p>
          <p><strong>Fecha de Nacimiento:</strong> {{ birthDate }}</p>
          <p><strong>País:</strong> {{ country }}</p>
          <p><strong>Sexo:</strong> {{ gender }}</p>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        name: "Luis Javier Espinal Duran",
        age: 20,
        birthDate: "13/01/25",
        country: "República Dominicana",
        gender: "Masculino",
      };
    },
  };
  </script>
  
  <style>
  body {
    font-family: Arial, sans-serif;
  }
  </style>  