List of scripts
1. job_script_expl_solv #MD job submission script for explicit solvent MD simulation. mdp files used are ions.mdp, minim.mdp, nvt.mdp, npt.mdp and md.mdp

2. job_script_in_vacuo #MD job submission script for invacuo MD simulation. mdp files used are ions.mdp, minim.mdp, nvt.mdp and md_nvt.mdp

3. sample_energy_cal #interaction energy calculation between EF hand 2 and metal ion (Nd3+)

4. fig_4e.ipnyb #ramachandran angle plot, with sample input files rama_y.xvg and rama_nd.xvg
5. gmx rama -f output_from_md.xtc -s output_from_md.tpr -o rama.xvg # gromacs command to calculate ramachandran angles for MD trajectory 
 
