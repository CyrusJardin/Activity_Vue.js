<script setup>
import { ref } from 'vue';

const inputText = ref('hello')
const employee = ref('')

</script>
<template>
    <div class="text-bg-dark p-3">
    <div  class="d-flex justify-content-center">
        <div class="d-flex p-2">
  <h3>  EMPLOYEE PROFILE</h3>
</div>
    <div class="mx-auto p-2" style="width: 400px; ">
    <select v-model="employee" class="form-select form-select-lg mb-3" aria-label="Large select example">
        <option value="1">Aliza Guetan</option>
        <option value="2">Mark Rala</option>
        <option value="3">Lyra Mercado</option>
        <option value="4">John Lloyd Gentolia</option>
        <option value="5">Ej-cien Balagoza</option>
        <option value="6">Shiena Geruela</option>
        <option value="7">Apple Mae Bon</option>
        <option value="8">Mikko Martinez</option>
        <option value="9">Mylen Javier</option>
        <option value="10">Jon Marion Gotera jr.</option>
    
    </select>
    <p v-if="employee == '1'">
        
        <h5>Name: Aliza Guetan</h5>
        <h5>Department: Department of Social welfare and Development</h5>
        <h5>Employment status: Permanent</h5>
        <h5>Position: Accountant</h5>
        <h5>Address: San Vicente,Bulan,Sorsogon</h5>
    </p>
    <p v-if="employee == '2'">
        <h5>Name: Mark Rala</h5>
        <h5>Department: Department of Public works and highway</h5>
        <h5>Employment status: Permanent</h5>
        <h5>Position: Public Engineer</h5>
        <h5>Address:Beguin,Bulan,Sorsogon</h5>
    </p>
    <p v-if="employee == '3'">
        <h5>Name: Lyra Mercado</h5>
        <h5>Department: Department of Social welfare and Development</h5>
        <h5>Employment status: Permanent</h5>
        <h5>Position: Head officer</h5>
        <h5>Address:Beguin,Bulan,Sorsogon</h5>
    </p>
    <p v-if="employee == '4'">
        <h5>Name: John Lloyd Gentolia</h5>
        <h5>Department: General Service Office</h5>
        <h5>Employment status: Permanent</h5>
        <h5>Position: Head officer</h5>
        <h5>Address:M.Roxas,Bulan,Sorsogon</h5>
    </p>
    <p v-if="employee == '5'">
        <h5>Name: Ej-cien Balagoza</h5>
        <h5>Department: General Service Office</h5>
        <h5>Employment status: Permanent</h5>
        <h5>Position: Inventory Section</h5>
        <h5>Address:San Vicente,Bulan,Sorsogon</h5>
    </p>
    <p v-if="employee == '6'">
        <h5>Name: Shiena Geruela</h5>
        <h5>Department: General Service Office</h5>
        <h5>Employment status: Permanent</h5>
        <h5>Position: Supply officer I</h5>
        <h5>Address:Zone 2,Bulan,Sorsogon</h5>
    </p>
    <p v-if="employee == '7'">
        <h5>Name: Apple Mae Bon</h5>
        <h5>Department: Kalahi</h5>
        <h5>Employment status: Permanent</h5>
        <h5>Position: Administrative Aide I</h5>
        <h5>Address:Nasuje,Bulan,Sorsogon</h5> 
    </p>
    <p v-if="employee == '8'">
        <h5>Name: Mikko Martinez</h5>
        <h5>Department: Kalahi</h5>
        <h5>Employment status: Permanent</h5>
        <h5>Position: Administrative Aide I</h5>
        <h5>Address:Aquino,Bulan,Sorsogon</h5>
    </p>
    <p v-if="employee == '9'">
        <h5>Name: Mylen Javier</h5>
        <h5>Department: General Service Office</h5>
        <h5>Employment status: Permanent</h5>
        <h5>Position: Administrative Aide I</h5>
        <h5>Address:Zone 8,Bulan,Sorsogon</h5>
    </p>
    <p v-if="employee == '10'">
        <h5>Name: Jon Marion Gotera Jr.</h5>
        <h5>Department: General Service Office</h5>
        <h5>Employment status: Permanent</h5>
        <h5>Position: Procurement</h5>
        <h5>Address:San Vicente,Bulan,Sorsogon</h5>
    </p>
    <!-- <p v-else>3</p> -->
</div>
</div>
</div>
</template>