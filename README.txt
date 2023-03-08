https://tutorcs.com
WeChat: cstutorcs
QQ: 749389476
Email: tutorcs@163.com
main_tb_v0.1.vhd - this is the main VHDL testbench, modify it as needed.

tb_vga_driver.v - this is the Verilog testbench for driving bmp images generator. DO NOT MODIFIY it. Only support VGA output resolution 640*480.

header_bmp.v - bmp header file. DO NOT MODIFIY it!

header_str.v - string coversion header. DO NOT MODIFIY it!

Please only add those files into your simulation hierachy (add sources -> add simulation sources...), do not include it into your implementation hierachy.

when you run simulation, it will generate your screen images in each frame named as xxx.bmp, and stored in the following directory:

assume xxxx is your project name

your project parent directory\xxxx.sim\sim_1\behav\xsim


