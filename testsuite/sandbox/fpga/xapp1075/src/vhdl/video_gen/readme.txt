*******************************************************************************
** � Copyright 2010 Xilinx, Inc. All rights reserved.
** This file contains confidential and proprietary information of Xilinx, Inc. and 
** is protected under U.S. and international copyright and other intellectual property laws.
*******************************************************************************
**   ____  ____ 
**  /   /\/   / 
** /___/  \  /   Vendor: Xilinx 
** \   \   \/    
**  \   \        video_gen\readme.txt
**  /   /        Date Last Modified: October 20, 2010
** /___/   /\    Date Created:       March 9, 2010
** \   \  /  \   
**  \___\/\___\ 
** 
**  Device: Virtex-6
**  Purpose: Virtex-6 Triple-Rate SDI Reference Design
**  Reference: 
**  Revision History: 
**      October 20, 2010: The VHDL version of the multigenHD_horz file was
**      modified to fix a startup issue that caused improper operation for a
**      brief period of time at startup.
**
**      July 26, 2010:  viden_pal.v was updated to correct its operation.
**
**      April 12, 2010: Readme update.
**
**      March 9, 2010: First release.
**   
*******************************************************************************
**
**  Disclaimer: 
**
**      This disclaimer is not a license and does not grant any rights to the materials 
**              distributed herewith. Except as otherwise provided in a valid license issued to you 
**              by Xilinx, and to the maximum extent permitted by applicable law: 
**              (1) THESE MATERIALS ARE MADE AVAILABLE "AS IS" AND WITH ALL FAULTS, 
**              AND XILINX HEREBY DISCLAIMS ALL WARRANTIES AND CONDITIONS, EXPRESS, IMPLIED, OR STATUTORY, 
**              INCLUDING BUT NOT LIMITED TO WARRANTIES OF MERCHANTABILITY, NON-INFRINGEMENT, OR 
**              FITNESS FOR ANY PARTICULAR PURPOSE; and (2) Xilinx shall not be liable (whether in contract 
**              or tort, including negligence, or under any other theory of liability) for any loss or damage 
**              of any kind or nature related to, arising under or in connection with these materials, 
**              including for any direct, or any indirect, special, incidental, or consequential loss 
**              or damage (including loss of data, profits, goodwill, or any type of loss or damage suffered 
**              as a result of any action brought by a third party) even if such damage or loss was 
**              reasonably foreseeable or Xilinx had been advised of the possibility of the same.


**  Critical Applications:
**
**      Xilinx products are not designed or intended to be fail-safe, or for use in any application 
**      requiring fail-safe performance, such as life-support or safety devices or systems, 
**      Class III medical devices, nuclear facilities, applications related to the deployment of airbags,
**      or any other applications that could lead to death, personal injury, or severe property or 
**      environmental damage (individually and collectively, "Critical Applications"). Customer assumes 
**      the sole risk and liability of any use of Xilinx products in Critical Applications, subject only 
**      to applicable laws and regulations governing limitations on product liability.

**  THIS COPYRIGHT NOTICE AND DISCLAIMER MUST BE RETAINED AS PART OF THIS FILE AT ALL TIMES.

*******************************************************************************

This folder contains video pattern generator modules used by the v6sdi_4rx4tx_demo
project. When rebuilding this demo, add all of the files in this folder to the
ISE project as source files.

The modules present in this folder are all documented in XAPP514.

