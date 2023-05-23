# Finding Representative Set

The repository has two folders including data for the Generalized tactical resource allocation problem (GTRAP) and multi-dimensional three-objective knapsack problem.

## GTRAP: 
The GTRAP is a model developed for GKN Aerospace AB,Sweden. The instances are made publicly accessible and the names of parts are sanitized. The model is capacitated multi-level resource allocation problem (<a href="https://link.springer.com/article/10.1007/s10287-023-00442-6">A criterion space decomposition approach to generalized tri-objective tactical resource allocation. Fotedar, Strömberg et.al</a>). The input parameters required are processing times, qualification costs, upper bounds on inventory, demand. The data shared here consists of <a href="https://github.com/SunneyF/FindingRepresentativeSet/blob/main/GTRAP/constant_data.csv">Constant data</a>, that is same across all the 15 instances. Instance specific data is stored in <a href="https://github.com/SunneyF/FindingRepresentativeSet/blob/main/GTRAP/GTRAP_instances.zip">GTRAP instances</a>

## Three-dimensional knapsack problem (3KP):
The instances are taken from <a href="https://fenix.tecnico.ulisboa.pt/homepage/ist175325/instances">M. Mesquita-Cunha, J.R. Figueira and A.P. Barbosa-Póvoa</a>. The data is copied and stored here <a href="https://github.com/SunneyF/FindingRepresentativeSet/blob/main/3KP/Instances.zip"> 3KP Instances</a>. However, we have randomly chosen 10 instances per class for assessment <a href="https://github.com/SunneyF/FindingRepresentativeSet/blob/main/3KP/Instances_3kp.zip"> 3KP instances
<!DOCTYPE html>
<html>
<head>
  <style>
    /* CSS styling for the illustrations */
    .folder {
      display: inline-block;
      margin: 10px;
    }

    .subfolder {
      margin-left: 20px;
    }
  </style>
</head>
<body>
  <h1>Folder Structure</h1>

  <div class="folder">
    <h2>Main Folder</h2>
    <ul>
      <li class="subfolder">
        <h3>Subfolder 1 (n1-g1)</h3>
        <ul>
          <li>file1.dat</li>
          <li>file2.dat</li>
          <li>...</li>
          <li>file10.dat</li>
        </ul>
      </li>
      <li class="subfolder">
        <h3>Subfolder 2 (n2-g2)</h3>
        <ul>
          <li>file1.dat</li>
          <li>file2.dat</li>
          <li>...</li>
          <li>file10.dat</li>
        </ul>
      </li>
      <!-- Repeat the structure for other subfolders -->
    </ul>
  </div>
</body>
</html>

