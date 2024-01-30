# Rainfall

## Objectives

This project is a **modest introduction** to the wide world of cyber security.  A world where you'll gave no margin for errors.  

It aims to discover, through several little challenges, cyber security in various fields.  

In the repository, you'll find as many **folders** as there are **levels**. In this folders, a text file named **"walkthrough"** that brings all the explanation to pass each levels.  
The file **.pass** in the level folder refers to the pass of the next level, the file source is the "ez-understanding" of what happend in the binary. That's the new step of this project, reverse engineering.

## Usage

To make this project, we have to use a VM (64bits) and starts it with the ISO provided with the subject. Once the machine is started, an IP is provided to connect with ssh.  

`ssh levelX@IP -p 4242`  

The username and password is level0 - level0, the username will increase as we go along in the project (level1, 2... until level9) and bonus part starts at bonus0.  
For each levels we have to exploit a binary found on the home repository to get access to the .pass file of the next user level.  

## Authors
<table>
  <tr>
    <td align="center"><a href="https://github.com/William-Dbt/"><img src="https://avatars.githubusercontent.com/u/16923245?v=4" width="100px;" alt=""/></a><br /><sub><b>wdebotte</b></sub><br /><a href="https://profile.intra.42.fr/users/wdebotte" title="Intra 42"><img src="https://img.shields.io/badge/Paris-FFFFFF?style=plastic&logo=42&logoColor=000000" alt="Intra 42"/></a></td>
    <td align="center"><a href="https://github.com/GAsNA"><img src="https://avatars.githubusercontent.com/u/58465901?v=4" width="100px;" alt=""/></a><br /><sub><b>rleseur</b></sub><br /><a href="https://profile.intra.42.fr/users/rleseur" title="Intra 42"><img src="https://img.shields.io/badge/Paris-FFFFFF?style=plastic&logo=42&logoColor=000000" alt="Intra 42"/></a></td>
  </tr>
</table>

[![rleseur's 42 stats](https://badge42.vercel.app/api/v2/cl7s08vet00110gmnrmm2benl/stats?cursusId=21&coalitionId=45)](https://github.com/JaeSeoKim/badge42)
