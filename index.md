
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Network Engineer CV</title>

  <!-- Tailwind CDN -->
  <script src="https://cdn.tailwindcss.com"></script>

  <script>
    tailwind.config = {
      darkMode: 'class',
    }
  </script>
</head>

<body class="bg-gray-100 dark:bg-gray-900 text-gray-900 dark:text-gray-100 transition">

<div class="max-w-4xl mx-auto p-6">

  <!-- Header -->
  <div class="flex justify-between items-center mb-6">
    <div>
      <h1 class="text-3xl font-bold">Your Name</h1>
      <p class="text-gray-500">Network Operations Engineer</p>
      <p class="text-sm">Email | Phone | GitHub | LinkedIn</p>
    </div>

    <div class="flex gap-2">
      <button onclick="toggleDark()" class="px-3 py-2 border rounded">🌙</button>
      <button onclick="downloadPDF()" class="px-3 py-2 bg-black text-white rounded">PDF</button>
    </div>
  </div>

  <!-- Summary -->
  <div class="bg-white dark:bg-gray-800 p-4 rounded shadow mb-4">
    <h2 class="text-xl font-semibold mb-2">Summary</h2>
    <p>
      Network Operations Engineer with experience in dual-ISP, BGP, OSPF, MPLS, and IPsec VPN.
      Skilled in troubleshooting, high availability, and data center networking.
    </p>
  </div>

  <!-- Skills -->
  <div class="bg-white dark:bg-gray-800 p-4 rounded shadow mb-4">
    <h2 class="text-xl font-semibold mb-2">Technical Skills</h2>
    <div class="grid grid-cols-2 gap-2 text-sm">
      <span>Routing: OSPF, BGP</span>
      <span>MPLS, VRF</span>
      <span>VPN: IPsec, GRE, FlexVPN</span>
      <span>Switching: VLAN, STP</span>
      <span>Tools: Wireshark</span>
      <span>Platforms: Cisco, MikroTik</span>
    </div>
  </div>

  <!-- Experience -->
  <div class="bg-white dark:bg-gray-800 p-4 rounded shadow mb-4">
    <h2 class="text-xl font-semibold mb-2">Experience</h2>

    <div class="mb-3">
      <h3 class="font-bold">Network Operations Engineer</h3>
      <p class="text-sm text-gray-500">Company | 2022 - Present</p>
      <ul class="list-disc ml-5 text-sm">
        <li>Managed dual-ISP redundancy</li>
        <li>Configured BGP and OSPF routing</li>
        <li>Maintained IPsec VPN tunnels</li>
      </ul>
    </div>

  </div>

  <!-- Projects -->
  <div class="bg-white dark:bg-gray-800 p-4 rounded shadow mb-4">
    <h2 class="text-xl font-semibold mb-2">Projects</h2>
    <ul class="list-disc ml-5 text-sm">
      <li>Captive portal with restricted internet access</li>
      <li>Network monitoring automation scripts</li>
    </ul>
  </div>

  <!-- Education -->
  <div class="bg-white dark:bg-gray-800 p-4 rounded shadow mb-4">
    <h2 class="text-xl font-semibold mb-2">Education</h2>
    <p>Master of Engineering (In Progress)</p>
  </div>

</div>

<script>
function toggleDark() {
  document.documentElement.classList.toggle('dark');
}

function downloadPDF() {
  window.print();
}
</script>

</body>
</html>
