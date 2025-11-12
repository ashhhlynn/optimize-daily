# Optimize Daily
<table>
  <tr>
    <td>
Daily fantasy football lineup builder and optimizer built with Node.js and React.js, featuring DraftKings contest data and Sleeper projections. Build DraftKings contest lineups manually from player queue or generate highest projected lineups under position and salary constraints through linear programming. Updated weekly during NFL season for the Sunday Classic and two Showdown contests.  
    </td>
  </tr>
</table> 

#### :link: <a href="https://optimize-daily.netlify.app/">Website</a>

### Technologies
- JavaScript
- React.js
- Node.js
- Express.js
- DraftKings API
- Sleeper API
- lp-solver.js
- Semantic UI React
- HTML & CSS
- Netlify & Render

### Features
- Fetch from DraftKings API to access live TNF/MNF Showdown and Sunday Classic contest data
- Fetch from Sleeper API to access player projections for week in PPR scoring 
- Sort player queue by position, name, FFPG, projection, and salary
- Manually add (or remove) players to lineup from queue
- Option to lock specific players from queue as required in optimization
- Optimize with lp-solver.js for highest projected lineup under salary and position constraints 
- Display lineup projection and remaining salary totals 
  
### Media 
<img src="https://github.com/ashhhlynn/optimize-fantasy-football/assets/84604278/d2a85433-04ff-4d3e-b89b-2ba3f6afded0" style="width:80%; height:80%">
<img src="https://github.com/ashhhlynn/optimize-fantasy-football/assets/84604278/80af461d-e490-4ba9-831a-f17d04faa4b0" style="width:80%; height:80%">

### Setup
   ```sh
   $ git clone https://github.com/ashhhlynn/optimize-daily.git
   ```
   ```sh
   $ cd optimize-daily
   ```
   ```sh
   $ cd client
   ```
   ```sh
   $ npm install
   ```
   ```sh
   $ npm start
   ```
### License 
This project is MIT licensed.
