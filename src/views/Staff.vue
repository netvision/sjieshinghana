<template>
    <div id="teaching">
    <h2 class="text-3xl mx-14 pt-16 pb-0 font-serif border-b-2 border-orange-500 w-10/12">Teaching &amp; Non-teaching Staff</h2>
    <table class="items-center bg-transparent border-collapse w-10/12 m-10">
        <thead>
          <tr>
            <th class="px-6 bg-blueGray-50 text-blueGray-500 align-middle border border-solid border-blueGray-100 py-3 text-xs uppercase border-l-0 border-r-0 whitespace-nowrap font-semibold text-left">
                          Staff Type
                        </th>
          <th class="px-6 bg-blueGray-50 text-blueGray-500 align-middle border border-solid border-blueGray-100 py-3 text-xs uppercase border-l-0 border-r-0 whitespace-nowrap font-semibold text-left">
                          Name
                        </th>
           <th class="px-6 bg-blueGray-50 text-blueGray-500 align-middle border border-solid border-blueGray-100 py-3 text-xs uppercase border-l-0 border-r-0 whitespace-nowrap font-semibold text-left">
                          Post
                        </th>
          <th class="px-6 bg-blueGray-50 text-blueGray-500 align-middle border border-solid border-blueGray-100 py-3 text-xs uppercase border-l-0 border-r-0 whitespace-nowrap font-semibold text-left">
                          Appointment Date
                        </th>
          <th class="px-6 bg-blueGray-50 text-blueGray-500 align-middle border border-solid border-blueGray-100 py-3 text-xs uppercase border-l-0 border-r-0 whitespace-nowrap font-semibold text-left">
                          Aadhar No.
                        </th>
          <th class="px-6 bg-blueGray-50 text-blueGray-500 align-middle border border-solid border-blueGray-100 py-3 text-xs uppercase border-l-0 border-r-0 whitespace-nowrap font-semibold text-left">
                          PAN No.
                        </th>
          </tr>
        </thead>

        <tbody>
          <tr v-for="s in staff">
            <th class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4 text-left text-blueGray-700 ">
              {{ s["Designation"] }}
            </th>
            <td class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4 ">
              {{ s["Name of Teacher"] }}
            </td>
            <td class="border-t-0 px-6 align-center border-l-0 border-r-0 text-xs whitespace-nowrap p-4">
              {{ s["Post"] }}
            </td>
            <td class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4">
              {{ s["appointment Date"] }}
            </td>
            <td class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4">
              {{ s["Aadhar Number"] }}
            </td>
            <td class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4">
              {{ s["PAN No "] }}
            </td>
          </tr>
        </tbody>
      </table>
  </div>
</template>
<script setup>
const staff = [
 {
  "Designation": "Principle",
  "Name of Teacher": "Dr. NEELAM  ",
  "PAN No ": "AHLPN6496K",
  "Subject": "EDUCATION",
  "Post": "PRINCIPAL",
  "appointment Date": "01\/04\/2024",
  "Aadhar Number": "4715 0464 8175"
 },
 {
  "Designation": "Teaching",
  "Name of Teacher": "BABLESH",
  "PAN No ": "BPCNB2318F",
  "Subject": "EDUCATION",
  "Post": "TEACHER",
  "appointment Date": "01\/03\/2020",
  "Aadhar Number": "9736 3478 7050"
 },
 {
  "Designation": "Teaching",
  "Name of Teacher": "NIDHI SHARMA",
  "PAN No ": "BCDMS4543F",
  "Subject": "EDUCATION",
  "Post": "TEACHER",
  "appointment Date": "02\/08\/2020",
  "Aadhar Number": "4776 8505 7694"
 },
 {
  "Designation": "Teaching",
  "Name of Teacher": "MAMTA KUMARI",
  "PAN No ": "LTVPK2818L",
  "Subject": "EDUCATION",
  "Post": "TEACHER",
  "appointment Date": "05\/12\/2020",
  "Aadhar Number": "3818 4760 5101"
 },
 {
  "Designation": "Teaching",
  "Name of Teacher": "GOPI RAM",
  "PAN No ": "AYMPR5735P",
  "Subject": "EDUCATION",
  "Post": "TEACHER",
  "appointment Date": "01\/07\/2016",
  "Aadhar Number": "6308 5013 6404"
 },
 {
  "Designation": "Teaching",
  "Name of Teacher": "RAKESH KUMAR",
  "PAN No ": "AYMPK6253P",
  "Subject": "EDUCATION",
  "Post": "TEACHER",
  "appointment Date": "02\/01\/2018",
  "Aadhar Number": "2018 1123 4852"
 },
 {
  "Designation": "Teaching",
  "Name of Teacher": "SAWITREE",
  "PAN No ": "BPTCS5698A",
  "Subject": "EDUCATION",
  "Post": "TEACHER",
  "appointment Date": "01\/03\/2020",
  "Aadhar Number": "6268 5542 3390"
 },
 {
  "Designation": "Teaching",
  "Name of Teacher": "AVINASH CHOUDHARY",
  "PAN No ": "ANYPC1293N",
  "Subject": "EDUCATION",
  "Post": "TEACHER",
  "appointment Date": "03\/07\/2013",
  "Aadhar Number": "6039 6663 6596"
 },
 {
  "Designation": "Teaching",
  "Name of Teacher": "ANJU SAINI",
  "PAN No ": "ATSPD3216G",
  "Subject": "EDUCATION",
  "Post": "TEACHER",
  "appointment Date": "05\/07\/2023",
  "Aadhar Number": "5502 3859 5458"
 },
 {
  "Designation": "Teaching",
  "Name of Teacher": "MANOJ SINGH",
  "PAN No ": "ATRPS6548A",
  "Subject": "EDUCATION",
  "Post": "TEACHER",
  "appointment Date": "05\/07\/2020",
  "Aadhar Number": "9914 0643 3599"
 },
 {
  "Designation": "Non-Teaching",
  "Name of Teacher": "AJAY KUMAR",
  "PAN No ": "DDIPK9204E",
  "Subject": "NA",
  "Post": "CLERCK",
  "appointment Date": "02\/07\/2022",
  "Aadhar Number": "4178 8044 1043"
 },
 {
  "Designation": "Non-Teaching",
  "Name of Teacher": "RAMESH KUMAR",
  "PAN No ": "FSQPK6595D",
  "Subject": "NA",
  "Post": "STORE KEEPAR",
  "appointment Date": "02\/01\/2018",
  "Aadhar Number": "8237 5538 2067"
 },
 {
  "Designation": "Teaching",
  "Name of Teacher": "KUSUM LATA",
  "PAN No ": "ALSPL6434C",
  "Subject": "EDUCATION",
  "Post": "TEACHER",
  "appointment Date": "02\/12\/2023",
  "Aadhar Number": "8287 1275 4202"
 },
 {
  "Designation": "Teaching",
  "Name of Teacher": "RAJESH KUMARI",
  "PAN No ": "GDMPK9582A",
  "Subject": "EDUCATION",
  "Post": "TEACHER",
  "appointment Date": "03\/07\/2023",
  "Aadhar Number": "4339 1015 9846"
 },
 {
  "Designation": "Non-Teaching",
  "Name of Teacher": "SHASHI KANT SHARMA",
  "PAN No ": "CAQPS7921A",
  "Subject": "NA",
  "Post": "ACCOUNTANT",
  "appointment Date": "02\/12\/2022",
  "Aadhar Number": "3810 5049 8907"
 },
 {
  "Designation": "Teaching",
  "Name of Teacher": "SAMATA SRIVASTAV",
  "PAN No ": "CDMPS3645F",
  "Subject": "EDUCATION",
  "Post": "TEACHER",
  "appointment Date": "02\/07\/2021",
  "Aadhar Number": "8621 9901 8917"
 },
 {
  "Designation": "Non-Teaching",
  "Name of Teacher": "ROSHAN",
  "PAN No ": "NA",
  "Subject": "NA",
  "Post": "NA",
  "appointment Date": "18-11-2021",
  "Aadhar Number": "6656 1286 1863"
 },
 {
  "Designation": "Teaching",
  "Name of Teacher": "KHUSHBOO",
  "PAN No ": "BAHPD2650R",
  "Subject": "EDUCATION",
  "Post": "TEACHER",
  "appointment Date": "02\/12\/2023",
  "Aadhar Number": "5245 3489 9993"
 },
 {
  "Designation": "Teaching",
  "Name of Teacher": "RAMESH CHAND AGARWAL",
  "PAN No ": "AUVPA6895A",
  "Subject": "EDUCATION",
  "Post": "TEACHER",
  "appointment Date": "04\/10\/2020",
  "Aadhar Number": "7744 5318 8718"
 },
 {
  "Designation": "Teaching",
  "Name of Teacher": "NARESH KUMAR GANESH",
  "PAN No ": "DMPGT1263M",
  "Subject": "EDUCATION",
  "Post": "PHYSICAL EDUCATION TEACHER",
  "appointment Date": "05\/05\/2015",
  "Aadhar Number": "5888 6356 1899"
 }
]
console.log(staff[0]["Aadhar Number"])
</script>