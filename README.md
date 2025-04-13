

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Simulation </h1>
  <p>
In this tutorial, we will go through creating a ticket as a user and working through the resolution of the ticket, then closing the ticket.
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
<img width="841" alt="Screenshot" src="https://i.imgur.com/RZzPtsd.png" />
    </td>
  </tr>
</table>

</p>
<p>
  Begin by entering http://localhost/osTicket into the browser. This will bring us to the end-user ticket creation page. Here we can submit a ticket as Karen (I created her in the admin panel prior). Once the ticket you created is submitted, use this link http://localhost/osTicket/scp/login.php to log in as one of the agents you created I'm going to use Peter Parker. 
</p>
<br>
<table>
  <tr>
    <td>
            <img  width="800" alt="Screenshot" src="https://i.imgur.com/9y7uN49.png" />
    </td>
    <td>
          <img width="650" alt="Screenshot" src="https://i.imgur.com/5bZfucx.png" />
    </td>
  </tr>
</table>

<p>Now that Karen has submitted a ticket regarding the software issue. Lets take a look at it as agent.</p>
<P>We can assign the ticket to Peter as or the Accounting team we created. Click the ticket -> Assigned To -> drop-down menu, then click Peter. Take note of the SLA and priority. These can be modified if needed when we find out more about the ticket. </P>
<br>



<img height="80%" width="80%"  alt="Screenshot" src="https://i.imgur.com/UCvSaRK.png" />

<p>Now, as an agent, we can acknowledge Karen's ticket and begin "working" it to completion. We can first acknowledge the ticket by replying publicly to Karen</p>
<p>When using the internal notes tab, we can submit notes that only the support team can see. It is helpful to communicate with agents regarding the progress of the ticket or new developments. </p>
<br>

<img height="80%" width="80%" alt="Screenshot" src="https://i.imgur.com/Xo8d24L.png" />
<p>
  osTicket keeps track of all correspondence between the agents and users to keep track of progress.
</p>
<br>

<table>
  <tr>
    <td>
<img width="950" alt="Screenshot" src="https://i.imgur.com/azLwvPP.png" />
    </td>
    <td>
<img width="841" alt="Screenshot" src="https://i.imgur.com/2FdIO95.png" />
    </td>
  </tr>
</table>

<p>Once the ticket is resolved, we can scroll up to the top and change the status to "resolved". You have an option to write a note in the prompt to give final notes about the ticket it would be good practice to possibly put the solution in that note. </p>

<br>
<img height="80%" width="80%" alt="Screenshot" src="https://i.imgur.com/Pyrfy8P.png" />
<p>
 In the overview page under the tickets tab, we can view closed tickets. These are tickets that have been resolved and closed.
</p>


**This concludes the Ticket Simulation lab! Thanks for following along, feel free to mess around with osTicket to see the other things you can do with the software**
