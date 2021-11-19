---
layout: archive
title: ""
permalink: /Research/
author_profile: true
---

<table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;"><tbody>
     <tr>
          <td style="padding:20px;width:50%;vertical-align:top">
           <img src='/papers_files/Safety_Critical/Algorithm.png' width="220">
            <br>
              <img src='/papers_files/Safety_Critical/Policy_Demo.jpg' width="220">
         </td>
         <td style="padding:20px;width:50%;vertical-align:middle">
           <a href="https://arxiv.org/abs/2109.02791">
               <papertitle><strong>Safe-Critical Modular Deep Reinforcement Learning with Temporal Logic through Gaussian Processes and Control Barrier Functions</strong></papertitle>
           </a>
           <br>
           <strong>Mingyu Cai</strong>,
           <a href="https://cristianvasile.com/">Cristian-Ioan Vasile</a>
           <br>
           <em>In submission</em>, 2021.
           <br>
           <a href="https://www.youtube.com/watch?v=fkCyAgx_FWM/">video</a> /
           <a href="https://arxiv.org/abs/2109.02791">PDF</a>
           <p></p>
           <p>Reinforcement learning (RL) is a promising approach. However, success is limited towards real-world applications, because ensuring safe exploration and facilitating adequate exploitation is a challenge for controlling robotic systems with unknown models and measurement uncertainties. The learning problem becomes even more difficult for complex tasks over continuous state-space and action-space. In this paper, we propose a learning-based control framework consisting of several aspects: (1) we leverage Linear Temporal Logic (LTL) to express complex tasks over an infinite horizons that are translated to a novel automaton structure; (2) we propose an innovative reward scheme for RL-agents with the formal guarantee that global optimal policies maximize the probability of satisfying the LTL specifications; (3) based on a reward shaping technique, we develop a modular policy-gradient architecture exploiting the benefits of the automaton structure to decompose overall tasks and enhance the performance of learned controllers; (4) by incorporating Gaussian Processes (GPs) to estimate the uncertain dynamic systems, we synthesize a model-based safeguard using Exponential Control Barrier Functions (ECBFs) for systems with high-order relative degrees. In addition, we utilize the properties of LTL automata and ECBFs to develop a guiding process to further improve the efficiency of exploration. </p>
         </td>
  </tr>

</tbody></table>

          </tbody></table>
          
          
                <table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;"><tbody>
             <td style="padding:20px;width:30%;vertical-align:top">
              <img src='images/se3hamdl/gif/trajtracking.gif' width="220">
               <br>
                 <img src='images/se3hamdl/gif/traj_results.gif' width="220">
                 <br>
                 <img src='images/se3hamdl/gif/tracking_results.gif' width="220">
                 <p> <center> Trajectory tracking + learned dynamics</center></p>
            </td>
            <td style="padding:20px;width:80%;vertical-align:middle">
              <a href="https://thaipduong.github.io/SE3HamDL/">
                  <papertitle>Hamiltonian-based Neural ODE Networks on the SE(3) Manifold For Dynamics Learning and Control</papertitle>
              </a>
              <br>
              <strong>Thai Duong</strong>,
              <a href="https://natanaso.github.io/">Nikolay Atanasov</a>
              <br>
              <em>RSS</em>, 2021.
              <br>
              <a href="https://thaipduong.github.io/SE3HamDL/">website</a> /
              <a href="https://thaipduong.github.io/SE3HamDL/">video</a> /
              <a href="https://arxiv.org/abs/2106.12782">arXiv</a>
              <p></p>
              <p>The dynamics of many robots, including ground, aerial, and underwater vehicles, are described in terms of their SE(3) pose and generalized velocity, and satisfy conservation of energy principles. This paper proposes a Hamiltonian formulation over the SE(3) manifold of the structure of a neural ordinary differential equation (ODE) network to approximate the dynamics of a rigid body. In contrast to a black-box ODE network, our formulation guarantees total energy conservation by construction. We develop energy shaping and damping injection control for the learned, potentially underactuated SE(3) Hamiltonian dynamics to enable a unified approach for stabiliziation and trajectory tracking with various platforms, including pendulum, rigid-body, and quadrotor systems.</p>
                <img src='images/se3hamdl/gif/data2.gif' width="180">
                <img src='images/se3hamdl/gif/data11.gif' width="180">
                <img src='images/se3hamdl/gif/data15.gif' width="180">
                <br>
                <img src='images/se3hamdl/gif/data14.gif' width="180">
                <img src='images/se3hamdl/gif/data13.gif' width="180">
                <img src='images/se3hamdl/gif/data3.gif' width="180">
                <p><center>Data collection from manual flights</center></p>
            </td>
          </tr>

          </tbody></table>
