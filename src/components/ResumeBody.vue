<template>
    <div class="resumee">
        <ul id="education">
            <h2>Education</h2>
            <li><h3>SEP2022 - JUL2023 - COMPUTER WEB PROGRAMMING:</h3>BYU-IDAHO</li> <img src="byu-i.png" alt="" width="55px">
            <li><h3>FEB2023 - JUL2023 - FULLSTACK PYTHON:</h3>Codo a Codo 4.0:</li>
            <li><h3>SEP2021 - JUL2022 - PROGRAMMING BUILDING BLOCKS:</h3>BYU-Pathway </li><img src="byu-p.png" alt="" width="80px">
            <li><h3>MAR2010 - DEC2016 - SENIOR MASTER OF WORKS:</h3>Esc Technician 3</li>
        </ul>
        <ul id="experience">
            <h2>Experience</h2>
            <li><h3>FEB2022 - CURRENT - FREELANCER:</h3>Translate, Web Development, Marketing</li>
            <li><h3>OCT2021 - DEC2023 - SALESMAN AND TELEMARKETING:</h3>Online sales</li>
            <li><h3>SEP2020 - JUN2021 - ADMINISTRATIVE FINANCIAL:</h3>The Church Of JesusChrist Of-Latter Saints</li><img src="church.png" alt="" width="45px">
            <li><h3>NOV2018 - JUN2019 - SELLER IN STORE: </h3>Supplies for Babies and Childrens</li>
            <li><h3>JUN2015 - JUL2018 - WORK MANAGER</h3>Contractor</li>
        </ul>
        
    </div>
</template>

<style scoped>

.resumee {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
    align-items: start;
}

#education,
#experience {
    background-color: white;
    text-align: left;
}

@media screen and (max-width: 768px) {
    .resumee {
        display: block;
    }
}

</style>