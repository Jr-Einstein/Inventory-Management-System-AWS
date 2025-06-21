<table>
  <tr>
    <td>
      <img src="https://github.com/user-attachments/assets/9b3816ba-9008-4f19-9d49-a15a3fb3d4af" alt="AMSTOCK Logo" width="100"/>
    </td>
    <td>
      <h1>AMSTOCK – Cloud-Native Inventory Management Platform with AWS Cloud Architecture</h1>
    </td>
  </tr>
</table>


> A full-stack inventory management system designed to scale with cloud-native architecture, leveraging modern technologies like Next.js, Node.js, PostgreSQL, and AWS services (EC2, RDS, S3, Amplify, API Gateway, and more).

---

## 🧰 Tech Stack & Tools Used

<div align="center">

<!-- Frontend -->
<img src="https://img.shields.io/badge/Next.js-black?logo=next.js&style=for-the-badge" />
<img src="https://img.shields.io/badge/TailwindCSS-06B6D4?logo=tailwindcss&style=for-the-badge" />
<img src="https://img.shields.io/badge/Redux%20Toolkit-764ABC?logo=redux&logoColor=white&style=for-the-badge" />
<img src="https://img.shields.io/badge/Recharts-FF6F61?logo=chart.js&style=for-the-badge" />

<!-- Backend -->
<img src="https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white&style=for-the-badge" />
<img src="https://img.shields.io/badge/Express.js-000000?logo=express&style=for-the-badge" />
<img src="https://img.shields.io/badge/Prisma-2D3748?logo=prisma&style=for-the-badge" />

<!-- Database -->
<img src="https://img.shields.io/badge/PostgreSQL-336791?logo=postgresql&logoColor=white&style=for-the-badge" />

<!-- AWS Services -->
<img src="https://img.shields.io/badge/AWS%20EC2-FF9900?logo=amazon-ec2&logoColor=white&style=for-the-badge" />
<img src="https://img.shields.io/badge/AWS%20RDS-527FFF?logo=amazon-rds&logoColor=white&style=for-the-badge" />
<img src="https://img.shields.io/badge/AWS%20S3-F29100?logo=amazon-s3&logoColor=white&style=for-the-badge" />
<img src="https://img.shields.io/badge/AWS%20Amplify-FF9900?logo=aws-amplify&logoColor=white&style=for-the-badge" />
<img src="https://img.shields.io/badge/API%20Gateway-FF4F00?logo=amazon-api-gateway&logoColor=white&style=for-the-badge" />
<img src="https://img.shields.io/badge/VPC%20Networking-232F3E?logo=amazonaws&logoColor=white&style=for-the-badge" />

</div>

---

## 🌐 Live Demo

[→ Click Here to Visit the Deployed App](https://main.dmhw3amscffi.amplifyapp.com/dashboard)

---

## 📸 Screenshots

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="https://github.com/user-attachments/assets/dbdf760e-8768-4aea-bf86-35ec46d8b60f" alt="Dashboard" width="550"/><br/><strong>Dashboard</strong>
      </td>
      <td align="center">
        <img src="https://github.com/user-attachments/assets/5e903e5c-e4c8-4021-8acb-24027bd9f285" alt="Products" width="550"/><br/><strong>Products</strong>
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="https://github.com/user-attachments/assets/6397c108-ef3d-4e98-9a39-b0cd3595fa91" alt="Inventory" width="550"/><br/><strong>Inventory</strong>
      </td>
      <td align="center">
        <img src="https://github.com/user-attachments/assets/972c696d-665b-4285-9716-5a94d3bd920e" alt="Expenses" width="550"/><br/><strong>Expenses</strong>
      </td>
    </tr>
  </table>
</div>

---

## 🔄 Data Flow Diagram

> [→ View Full Data Flow on DrawSQL](https://drawsql.app/teams/aman-51/diagrams/amstock-inventory-management-system-aws)

![image](https://github.com/user-attachments/assets/d13969dc-fa51-410a-8bdd-7f2dd3b32f92)



---

## ☁️ AWS Architecture Diagram

> [→ View AWS Architecture Diagram on Lucidchart](https://lucid.app/lucidchart/c3268d1a-f332-4741-bae0-32ae40d67249/edit?viewport_loc=589%2C-298%2C2944%2C1287%2C0_0&invitationId=inv_8425f668-4648-4a1d-ac50-0c5611aa6ee9)


![image](https://github.com/user-attachments/assets/5aa7910e-9abc-46c5-a073-660b1df25b97)



---

## 📦 Features

- ➤ Real-time inventory listing and dynamic data updates  
- ➤ Full CRUD capabilities for products and stock management  
- ➤ Advanced filtering, pagination, and category-based search  
- ➤ Product image uploads integrated with S3 and dynamic rendering  
- ➤ Light/Dark theme toggle using Tailwind’s utility system  
- ➤ Authentication-ready structure for secure multi-user access  
- ➤ Data visualization using Recharts for inventory and expense stats  
- ➤ Complete separation of frontend and backend for scalability  
- ➤ Frontend CI/CD via Amplify; backend managed via EC2 + PM2  
- ➤ Multi-AZ RDS for database fault tolerance and auto-failover

---

## 🏗️ Deployment Architecture

- **Frontend (Next.js)** → Hosted on AWS Amplify with GitHub CI/CD pipelines, auto-builds triggered on push.  
- **Backend (Node.js/Express)** → Deployed on AWS EC2 within a private subnet, using PM2 for process reliability.  
- **Database (PostgreSQL)** → Provisioned on AWS RDS with Multi-AZ failover configuration and subnet isolation.  
- **Static Files (Images)** → Stored and served securely from AWS S3 with signed URL access control.  
- **API Layer** → Managed by AWS API Gateway, exposing secure REST endpoints from frontend to backend.  
- **Networking** → Isolated VPC setup with public/private subnets, NAT gateway, and strict security groups.

---

## 🛠️ Local Setup

```bash
# 1. Clone the repository
git clone https://github.com/Jr-Einstein/Inventory-Management-System-AWS.git
cd Inventory-Management-System-AWS

# 2. Install dependencies (frontend and backend)
cd client
npm install

cd ../server
npm install

# 3. Setup .env files
# Create and configure .env files in both /client and /server directories

# 4. Run the development servers
npm run dev  # Run separately in both folders
```






© 2025 AMSTOCK – Developed by Aman Kumar Singh. All rights reserved.
