---
layout: post
title:  "Ticket Display Board"
date:   2017-09-22 10:04:00 -0500
img: img/portfolio/TicketBoard.jpg
modalID: modalTicketBoard
order: 8
type: minor
carousel:
  - img: /img/portfolio/ticketboard/ticketboard1.jpg
  - img: /img/portfolio/ticketboard/ticketboard2.jpg
  - img: /img/portfolio/ticketboard/ticketboard3.jpg
---
The Ticket Display Board was a device I conceived of to keep track of currently open tickets at a previous employer. Tickets were divided between Bugs and Change Requests, and the board tracked the total number of tickets in each category, along with the number opened and closed that day. It also indicated the current trend with an arrow.

I was responsible for two hardware iterations of this project - one using an Ethernet-equipped Arduino, and a final one using a Raspberry Pi and Wifi. The final version used a PHP script to interface with a vendor-provided HTTP API for the ticket system, and used GPIOs to control a serial bus of seven-segment LED displays. Off-the-shelf 4-inch displays were used for the current totals. Custom LED boards were designed to use the same protocol as the large ones, but smaller digits. The whole unit was powered from a single 12V supply.