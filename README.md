#!/bin/bash
#Author: Manasa
#Date: 28 May
#Version: v1

#This script outputs the node health
####################

echo "Print the disk space"
df -h
echo"print the memory usage"
free -g
echo "print the CPU"
nproc
