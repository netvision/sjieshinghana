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
          <tr v-for="s in staff" :key="`${s.Name}-${s['PAN No.']}`">
            <th class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4 text-left text-blueGray-700 ">
              {{ s["Staff Type"] }}
            </th>
            <td class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4 ">
              {{ s["Name"] }}
            </td>
            <td class="border-t-0 px-6 align-center border-l-0 border-r-0 text-xs whitespace-nowrap p-4">
              {{ s["Post"] }}
            </td>
            <td class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4">
              {{ s["Appointment Date"] }}
            </td>
            <td class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4">
              {{ s["Aadhar No."] }}
            </td>
            <td class="border-t-0 px-6 align-middle border-l-0 border-r-0 text-xs whitespace-nowrap p-4">
              {{ s["PAN No."] }}
            </td>
          </tr>
        </tbody>
      </table>
  </div>
</template>
<script setup>
const staff = [
 {
  "Staff Type": "Principle",
  "Name": "Dr. Pritama Devi",
  "Post": "PRINCIPAL",
  "Appointment Date": "08/07/2025",
  "Aadhar No.": "4715 0464 8175",
  "PAN No.": "AHLPN6496K"
 },
 {
  "Staff Type": "Teaching",
  "Name": "AVINASH CHOUDHARY",
  "Post": "TEACHER",
  "Appointment Date": "01/07/2015",
  "Aadhar No.": "6039 6663 6596",
  "PAN No.": "ANYPC1293N"
 },
 {
  "Staff Type": "Teaching",
  "Name": "GOPI RAM",
  "Post": "TEACHER",
  "Appointment Date": "01/07/2015",
  "Aadhar No.": "6308 5013 6404",
  "PAN No.": "AYMPR5735P"
 },
 {
  "Staff Type": "Teaching",
  "Name": "KHUSHBOO",
  "Post": "TEACHER",
  "Appointment Date": "01/03/2025",
  "Aadhar No.": "5245 3489 9993",
  "PAN No.": "BAHPD2650R"
 },
 {
  "Staff Type": "Teaching",
  "Name": "SUNITA RANI",
  "Post": "TEACHER",
  "Appointment Date": "02/07/2025",
  "Aadhar No.": "6254 5956 9245",
  "PAN No.": "DPGPR0360E"
 },
 {
  "Staff Type": "Teaching",
  "Name": "ANJU SAINI",
  "Post": "TEACHER",
  "Appointment Date": "04/04/2023",
  "Aadhar No.": "5502 3859 5458",
  "PAN No.": "ATSPD3216G"
 },
 {
  "Staff Type": "Teaching",
  "Name": "SATYENDRA SINGH",
  "Post": "TEACHER",
  "Appointment Date": "30/01/2025",
  "Aadhar No.": "3605 1851 8771",
  "PAN No.": "ETZPS5212J"
 },
 {
  "Staff Type": "Teaching",
  "Name": "ANITA KUMAWAT",
  "Post": "TEACHER",
  "Appointment Date": "10/07/2024",
  "Aadhar No.": "9415 2685 6368",
  "PAN No.": "GBIPK2723R"
 },
 {
  "Staff Type": "Teaching",
  "Name": "AJAY KUMAR",
  "Post": "TEACHER",
  "Appointment Date": "10/10/2025",
  "Aadhar No.": "4178 8044 1043",
  "PAN No.": "DDIPK9204E"
 },
 {
  "Staff Type": "Teaching",
  "Name": "PINKY CHOUDHARY",
  "Post": "TEACHER",
  "Appointment Date": "13/10/2025",
  "Aadhar No.": "8042 2979 1076",
  "PAN No.": "BTIPC0699H"
 },
 {
  "Staff Type": "Teaching",
  "Name": "VISHNU SAINI",
  "Post": "TEACHER",
  "Appointment Date": "13/10/2025",
  "Aadhar No.": "3888 9328 7781",
  "PAN No.": "OXXPS4435R"
 },
 {
  "Staff Type": "Teaching",
  "Name": "KIRAN CHOUDHARY",
  "Post": "TEACHER",
  "Appointment Date": "13/10/2025",
  "Aadhar No.": "8020 9896 0002",
  "PAN No.": "CCEPC4194F"
 },
 {
  "Staff Type": "Teaching",
  "Name": "MAMTA CHOUDHARY",
  "Post": "TEACHER",
  "Appointment Date": "13/10/2025",
  "Aadhar No.": "5802 4547 3496",
  "PAN No.": "DLYPC0412C"
 },
 {
  "Staff Type": "Teaching",
  "Name": "JITENDRA SINGHBAJROLIYA",
  "Post": "TEACHER",
  "Appointment Date": "13/10/2025",
  "Aadhar No.": "6457 7930 4286",
  "PAN No.": "ALUPB9061B"
 },
 {
  "Staff Type": "Teaching",
  "Name": "MISHRI CHANDIWAL",
  "Post": "TEACHER",
  "Appointment Date": "15/01/2025",
  "Aadhar No.": "3019 8785 9683",
  "PAN No.": "BSEPC6015L"
 },
 {
  "Staff Type": "Teaching",
  "Name": "SANIYA",
  "Post": "PHYSICAL EDUCATION TEACHER",
  "Appointment Date": "01/07/2024",
  "Aadhar No.": "2746 2958 0995",
  "PAN No.": "EBXPS6787J"
 },
 {
  "Staff Type": "Non-Teaching",
  "Name": "VIKASH KUMAR GURAWA",
  "Post": "LIBRARIAN",
  "Appointment Date": "09/07/2024",
  "Aadhar No.": "7777 6806 4064",
  "PAN No.": "DAYPK2309M"
 },
 {
  "Staff Type": "Non-Teaching",
  "Name": "SAMATA SRIVASTAV",
  "Post": "ACCOUNTANT",
  "Appointment Date": "02/12/2023",
  "Aadhar No.": "8261 9901 8917",
  "PAN No.": "CDMPS6563F"
 },
 {
  "Staff Type": "Non-Teaching",
  "Name": "SHASHI KANT SHARMA",
  "Post": "ACCOUNTANT",
  "Appointment Date": "01/07/2022",
  "Aadhar No.": "3810 5049 8907",
  "PAN No.": "CAQPS7921A"
 },
 {
  "Staff Type": "Non-Teaching",
  "Name": "ASHISH KUMAR",
  "Post": "LDC",
  "Appointment Date": "03/04/2023",
  "Aadhar No.": "4427 2412 7961",
  "PAN No.": "KWZPK0577D"
 },
 {
  "Staff Type": "Non-Teaching",
  "Name": "KAPIL KUMAR",
  "Post": "STORE KEEPAR",
  "Appointment Date": "01/08/2024",
  "Aadhar No.": "4035 8038 8917",
  "PAN No.": "ECMPK4823B"
 },
 {
  "Staff Type": "Non-Teaching",
  "Name": "RAMESH KUMAR",
  "Post": "PEON",
  "Appointment Date": "14/07/2021",
  "Aadhar No.": "8237 5538 2067",
  "PAN No.": "FSQPK6595D"
 }
]
</script>
