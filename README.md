# Hello-World
Hello World contract
//SPDX-License-Identifier: GPL-3.0
pragma solidity ^0.8.10;

contract Hello_World{

    string public hello_world;

    function setHello_World(string memory _hello_world) public{
        hello_world = _hello_world;
    }
    
    function viewHello_World() public view returns(string memory){
        return hello_world ;
    }
