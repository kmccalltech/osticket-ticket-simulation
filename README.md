

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Simulation </h1>
  <p>
In this tutorial we will go through creating a ticket as a user and working through the resolution of the ticket then closing the ticket.
</p>

  <h2>Prerequisites</h2>
  <p>-Install osTicket www.github.com/kmccalltech/osticket-prereqs</p>
  <p>-Configure osTicket www.github.com/kmccalltech/osticket-post-config</p>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Configuration Steps</h2>
<table>
  <tr>
    <td>
<img width="950" alt="Screenshot" src="https://i.imgur.com/P74um5d.png" />
    </td>
    <td>
<img width="841" alt="Screenshot" src="https://i.imgur.com/P74um5d.png" />
    </td>
  </tr>
</table>

</p>
<p>
  Begin by entering http://localhost/osTicket into the browser. This will bring us to the end user ticket creation page. Here we can submit a ticket as Karen (I created her in the admin panel prior). Once the ticket is created you created, use this link http://localhost/osTicket/scp/login.php to log in as one of the agents you created I'm going to use Peter Parker. 
</p>
<br>
<table>
  <tr>
    <td>
            <img  width="800" alt="Screenshot" src="" />
    </td>
    <td>
          <img width="650" alt="Screenshot" src="" />
    </td>
  </tr>
</table>

<p>Now that Karen has submitted a ticket regarding the software issue. Lets take a look at it as agent.</p>
<P>We can assign the ticket to Peter as or the Accounting team we created. Take note of the SLA and priority. These can be modified if needed when we find out more about the ticket. </P>
<br>



<img height="80%" width="80%"  alt="Screenshot" src="https://github.com/user-attachments/assets/2250bfde-a0cf-4fbf-a9c4-3cc86bebf5a2" />

<p>Now as an agent we can acknowledge Karen's ticket and begin "working" it to completion. We can first acknowledge the ticket by replying publicly to Karen</p>
<p>Using the internal notes tab, we can submit notes where only the support team can see. This is helpful to have communication between agents on the progress of the ticket or new developments. </p>
<br>

<img height="80%" width="80%" alt="Screenshot" src="https://github.com/user-attachments/assets/9e6cd9a8-1c35-48c8-9b0f-bcb8da1cf11c" />
<p>
  osTicket keeps track of all correspondance between the agents and users to keep track of progress.
</p>
<br>

<img height="80%" width="80%" alt="Screenshot" src="https://github.com/user-attachments/assets/724fa26e-a1ff-4acf-bce1-7b231e968f73" />

<p>Once we "work" this ticket to resolution, we can scroll up to the top and change the status to "resolved". In the overview page under the tickets tab, we can view closed tickets. These are tickets that have been resolved and closed. </p>

<br>
<img height="80%" width="80%" alt="Screenshot" src="https://github.com/user-attachments/assets/0ae0ed02-5aa9-4966-983b-954a49577862" />
<p>
To simulate ticket intake via phone or email, we can navigate to tickets as an agent and create a new ticket. The new ticket can be created based on the nature of the issue being reported.
</p>

<br>

<table>
  <tr>
    <td>
      <img  width="850" alt="Screenshot" src="https://github.com/user-attachments/assets/81bc8b2f-233a-4d7f-b255-dba8ac12c526" />
    </td>
    <td>
      <img  width="650" alt="Screenshot" src="https://github.com/user-attachments/assets/0d68afe8-eddd-4b70-bc83-9e3b357ceb72" />
    </td>
  </tr>
</table>

<p>We can submit replies to the ticket and "work" the ticket to resolution. The ticket can be given a priority and it can be assigned to an agent. As we learn more information about the ticket we can change various elements about the ticket like the SLA.
Instead of the entire department not being able to use Adobe we realize it is just 2 users, this prompts a change in the SLA. 
</p>

<img width="645" alt="Screenshot" src="https://github.com/user-attachments/assets/7e271417-843e-437e-9d82-1b8dd805b379" />

<p>Once we arrive at a resolution, we can change the status of the ticket at the top from "Open" to "Resolved". Hooray for ticket resolution!</p>

**There are lots of other things that can be done within osTicket so feel free to explore around to build more intuition with osTicket.**

**This conlcudes the Ticket Lifecycle lab!**
