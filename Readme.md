<!DOCTYPE HTML>
<HTML>

<HEAD>
   USG AI
</HEAD>

<BODY>
   <PRE>
Copy Right (c) 2022 Useop Gim
Affero GNU GPL v3 license 
https://github.com/Naptwen/usgAI
<details>
<summary># Comment</summary>
   I coded this program for creating an A. I with freedom under positive purpose
   for the world. So hope it is useful for mathematicians, programmers, scientists,
   and whoever is interested.
</details>
<details>
<summary># Reference and notation</summary>
   1. The origin of this software must not be misrepresented; you must not
   claim that you wrote the original software. If you use this software
   in a product, an acknowledgment in the product documentation would be
   appreciated but is not required.
   2. Altered source versions must be plainly marked as such,
   and must not be misrepresented as being the original software.
   3. This notice may not be removed or altered from any source distribution.
</details>
<details>
<summary># GNU, AFFERO LICENSE</summary>
   This file is part of the usg_AI Library
   you can redistribute it and/or modify it under the terms of the GNU Affero.
   Affero General Public License V3 as published by the Free Software
   Foundation. http://www.gnu.org/licenses/ But, WITHOUT ANY WARRANTY without
   even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR
   PURPOSE. See the GNU General Public License and Affero license for more details
</details>
<details>
<summary># STD C++ LICENSE</summary>
   The core part of standard c++ library is base on the using LLVM clang library
</details>
<details>
<summary># SPECIAL PROVISION</summary>
   To prevent and make users take responsibility, for the uncontrollable and
   unpredictable dangers in the future, a special provision for using this program
   for responsibility. This library is restricted about any purpose that breaks the
   Laws of Robotic including intentness, negligence, and recklessness also
   restricted and users take responsibility.
</details>
<details>
<summary># REFERENCE FOR BASE 64 SOURCE CODE</summary>

   base64.cpp and base64.h
   
   base64 encoding and decoding with C++.
   More information at
     https://renenyffenegger.ch/notes/development/Base64/Encoding-and-decoding-base-64-with-cpp

   Version: 2.rc.08 (release candidate)

   Copyright (C) 2004-2017, 2020, 2021 René Nyffenegger

   This source code is provided 'as-is', without any express or implied
   warranty. In no event will the author be held liable for any damages
   arising from the use of this software.

   Permission is granted to anyone to use this software for any purpose,
   including commercial applications, and to alter it and redistribute it
   freely, subject to the following restrictions:

   1. The origin of this source code must not be misrepresented; you must not
      claim that you wrote the original source code. If you use this source code
      in a product, an acknowledgment in the product documentation would be
      appreciated but is not required.

   2. Altered source versions must be plainly marked as such, and must not be
      misrepresented as being the original source code.

   3. This notice may not be removed or altered from any source distribution.

   René Nyffenegger rene.nyffenegger@adp-gmbh.ch
</details>
<details>
<summary># Khronos License For OpenGL, OpenCl, OpenCV</summary>
   The core part of OpenCL, OpenGL, OpenCV are following Khronos license
   https://www.khronos.org/legal/Khronos_Apache_2.0_CLA
</details>
</PRE>
</BODY>
<BLOCKQUOTE>
<summary># PATCH NOTE 2.3</summary>
<PRE>
Sep 03, 2022.
1. Fix : Edit the PPO algorithm for paraller multiplication
2. New : Construct GUI for OpenGL with GLFW and GLEW
3. New : Reading Screen as Video for using CNN algorithm
4. Future : Trying to change OpenGLES for application
</PRE>
</BLOCKQUOTE>
<BLOCKQUOTE>
<details>Tree
<BLOCKQUOTE>
The hovered text explains what is the function of header file and some header file is directly linked to the original code source website
</BLOCKQUOTE>
   <summary># API Hirechy</summary>
   <ul class="menu">
      <li>
         <a href="#"><button title="This is the main program">main.cpp</button></a>
         <ul class="submenu">
            <li><a href="#"><button title="This is for connection GUI">usg_Khronos.hpp</button></a></li>
            <ul class="submenu">
               <li><a href="#"><button title="This is for graphic and UI object">usg_OpenGL.hpp</button></button></a></li>
               <ul class="submenu">
                  <li><a href="#"><button title="This is for image and video">usg_OpenCV.hpp</button></a></li>
                  <ul class="submenu">
                     <li><a href="#"><button title="This is for fragment shader for 3d object">shader.frag</button></li>
                     <li><a href="#"><button title="This is for vertices shader for 3d object">shader.vert</button></li>
                     <li><a href="https://www.glfw.org/"><button title="This is for easy making OpenGL window">glfw3.h</button></li>
                     <li><a href="http://glew.sourceforge.net/"><button title="This is for easy making VAO for OpenGL">glew.h</button></li>
                     <li><a href="https://opencv.org/"><button title="This is for loading image">imgcode.h</button></li>
                     <li><a href="https://opencv.org/"><button title="This is for loading video">video.h</button></li>
                  </ul>
               </ul>
            </ul>
            <li><a href="#"><button title="This is for console user interface">usg_CLI.hpp</button></a></li>
            <ul class="submenu">
               <li><a href="#"><button title="This is for console interface for AI">usg_CLI_RL.hpp</button></a></li>
               <ul class="submenu">
                  <li><a href="#"><button title="This is for running AI program">usg_RL_AI.hpp</button></a></li>
                  <ul class="submenu">
                     <li><a href="#"><button title="This is for multi threading agents">usg_RL_hivemind.hpp</button></a></li>
                     <ul class="submenu">
                        <li><a href="#"><button title="This is for setting rule and enviroment">usg_RL_rule_book.hpp</button></a></li>
                        <ul class="submenu">
                           <li><a href="#"><button title="This is for RL model algorithm">usg_RL_model.hpp</button></a></li>
                           <ul class="submenu">
                              <li><a href="#"><button title="This is for Neurla network algorithm">usg_Neural.hpp</button></a></li>
                              <ul class="submenu">
                                 <li><a href="#"><button title="This is for Neurla network functions">usg_Neural_function.hpp</button></a></li>
                                 <ul class="submenu">
                                    <li><a href="#"><button title="This is for CNN network algorithm">usg_CNN.hpp</button></a></li>
                                    <ul class="submenu">
                                       <li><a href="#"><button title="This is for CNN network functions">usg_CNN_function.hpp</button></a></li>
                                       <ul class="submenu">
                                          <li><a href="#"><button title="This is for some convenient functinos">usg_etc_algorithm.hpp</button></a></li>
                                          <ul class="submenu">
                                             <li><a href="https://renenyffenegger.ch/notes/development/Base64/Encoding-and-decoding-base-64-with-cpp"><button title="This is to reduce file size and communicate through network ">base_64.h</button></a></li>
                                             <li><a href="#"><button title="This is for intersection between GPGPU and CPU">usg_vmatrix_Merge.hpp</button></a></li>
                                             <ul class="submenu">
                                                <li><a href="#"><button title="This is for matrix calculation algorithm base on standard vector container">usg_vmatrix.hpp</button></a></li>
                                                <li><a href="#"><button title="This is for OpenCL gpgpu kernel interchange algorithm">usg_OpenCL.hpp</button></a></li>
                                                <ul class="submenu">
                                                   <li><a href="#"><button title="This is for OpenCL">CL.h</button></a></li></ul>
                                          </ul>
                                       </ul>
                                    </ul>
                                 </ul>
                              </ul>
                           </ul>
                        </ul>
                     </ul>
                  </ul>
               </ul>
            </ul>
         </ul>
      </ul>
   </ul>
</details>
</BLOCKQUOTE>
</HTML>
