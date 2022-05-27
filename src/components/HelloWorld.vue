<template>
 <div>
    <table id="calculator" dir="ltr" style="text-align: center; margin: auto">
      <tr>
        <td colspan="5">
          <input
            v-model="screen"
            dir="ltr"
            id="result"
            type="number"
            style="padding: 5px; font-weight: bold; text-align: right"
          />
           </td>

        <td>
      </tr>        </td>
 
        <tr>
         <td><button @click="digit(1)" class="digit">1</button></td>
         <td><button @click="digit(2)" class="digit">2</button></td>
         <td><button @click="digit(3)" class="digit">3</button></td>
         <td><button @click="minus" id="minus">-</button></td>
         <td><button @click="mod" id="mod">%</button></td>
       </tr>