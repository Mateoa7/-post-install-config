<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo" />
</p>

<h1 align="center">osTicket - Prerequisites and Installation</h1>
<p align="center">This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.</p>

<h2>Environments and Technologies Used</h2>
<ul>
  <li>Microsoft Azure (Virtual Machines/Compute)</li>
  <li>Remote Desktop</li>
  <li>Internet Information Services (IIS)</li>
</ul>

<h2>Operating Systems Used</h2>
<ul>
  <li>Windows 10 (21H2)</li>
</ul>

<h2>Installation Steps</h2>

<ol>
  <li><strong>Access osTicket</strong>
    <ul>
      <li><strong>Admin/Analyst Login Page:</strong> <a href="http://localhost/osTicket/scp/login.php">http://localhost/osTicket/scp/login.php</a>
        <br />This is where administrators and agents manage the ticketing system.</li>
      <li><strong>End User osTicket URL:</strong> <a href="http://localhost/osTicket">http://localhost/osTicket</a>
        <br />This is the interface for customers to submit tickets.</li>
    </ul>
  </li>
  
  <li><strong>Acknowledge the Agent Panel vs Admin Panel</strong>
    <ul>
      <li><strong>Agent Panel:</strong> Where tickets are managed by staff (agents).</li>
      <li><strong>Admin Panel:</strong> Where you configure the system settings, roles, users, departments, etc.</li>
    </ul>
  </li>
  
  <li><strong>Configure osTicket</strong>
    <ul>
      <li><strong>Roles (Grouping Permissions):</strong>
        <ul>
          <li>Go to: <em>Admin Panel → Agents → Roles</em></li>
          <li>Example: Role: Supreme Admin (highest level of access).</li>
        </ul>
      </li>
      
  <img src="https://i.imgur.com/EZkP1mB.png" alt="osTicket logo" />

   
  <li><strong>Departments (Ticket Visibility):</strong>
    <ul>
      <li>Go to: <em>Admin Panel → Agents → Departments</em></li>
      <li>Examples:</li>
      <ul>
        <li>SysAdmins: Handles system administration issues.</li>
        <li>Help Desk: Handles general support tickets.</li>
        <li>Networking: Handles network-related issues.</li>
      </ul>
    </ul>
  </li>

  <li><strong>Teams (Combine Agents from Different Departments):</strong>
    <ul>
      <li>Go to: <em>Admin Panel → Agents → Teams</em></li>
      <li>Example: Team: Online Banking (agents from SysAdmins and Networking).</li>
    </ul>
  </li>

  <li><strong>Allow/Restrict Ticket Creation:</strong>
    <ul>
      <li>Go to: <em>Admin Panel → Settings → User Settings</em></li>
      <li>Options:</li>
      <ul>
        <li>Allow anyone to create tickets: Uncheck "Registration Required".</li>
        <li>Require login to create tickets: Check "Registration Required".</li>
      </ul>
    </ul>
  </li>

  <li><strong>Add Agents (Workers):</strong>
    <ul>
      <li>Go to: <em>Admin Panel → Agents → Add New</em></li>
      <li>Examples:</li>
      <ul>
        <li>Jane (Assigned to SysAdmins department).</li>
        <li>John (Assigned to Support department).</li>
      </ul>
    </ul>
  </li>

  <li><strong>Add Users (Customers):</strong>
    <ul>
      <li>Go to: <em>Agent Panel → Users → Add New</em></li>
      <li>Examples:</li>
      <ul>
        <li>Mateo1 and Mateo2 as customers who can submit tickets.</li>
      </ul>
    </ul>
  </li>

  <li><strong>Service Level Agreements (SLA):</strong>
    <ul>
      <li>Go to: <em>Admin Panel → Manage → SLA

  
  <li><strong>Test the Setup</strong>
    <ul>
      <li><strong>Customer Experience:</strong> Visit <a href="http://localhost/osTicket">http://localhost/osTicket</a> and create a test ticket as a user.</li>
      <li><strong>Agent Experience:</strong> Log in to <a href="http://localhost/osTicket/scp/login.php">http://localhost/osTicket/scp/login.php</a> and manage the ticket.</li>
      <li><strong>Admin Tasks:</strong> Adjust configurations or monitor ticket status in the Admin Panel.</li>
    </ul>
  </li>
</ol>
