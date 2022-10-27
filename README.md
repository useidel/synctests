# synctests
synctests

Build 27

Adding these three lines to the git config file after the fetch = +refs/:refs/ line fixed it for me:

push = +refs/heads/*:refs/heads/*

push = +refs/tags/*:refs/tags/*

push = +refs/change/*:refs/change/*
