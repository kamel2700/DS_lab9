# DS_lab9

```
rs.status()
{
	"set" : "rs0",
	"date" : ISODate("2019-10-31T20:43:12.845Z"),
	"myState" : 2,
	"term" : NumberLong(2),
	"syncingTo" : "member3:27017",
	"syncSourceHost" : "member3:27017",
	"syncSourceId" : 2,
	"heartbeatIntervalMillis" : NumberLong(2000),
	"majorityVoteCount" : 2,
	"writeMajorityCount" : 2,
	"optimes" : {
		"lastCommittedOpTime" : {
			"ts" : Timestamp(1572554586, 1),
			"t" : NumberLong(2)
		},
		"lastCommittedWallTime" : ISODate("2019-10-31T20:43:06.789Z"),
		"readConcernMajorityOpTime" : {
			"ts" : Timestamp(1572554586, 1),
			"t" : NumberLong(2)
		},
		"readConcernMajorityWallTime" : ISODate("2019-10-31T20:43:06.789Z"),
		"appliedOpTime" : {
			"ts" : Timestamp(1572554586, 1),
			"t" : NumberLong(2)
		},
		"durableOpTime" : {
			"ts" : Timestamp(1572554586, 1),
			"t" : NumberLong(2)
		},
		"lastAppliedWallTime" : ISODate("2019-10-31T20:43:06.789Z"),
		"lastDurableWallTime" : ISODate("2019-10-31T20:43:06.789Z")
	},
	"lastStableRecoveryTimestamp" : Timestamp(1572554546, 1),
	"lastStableCheckpointTimestamp" : Timestamp(1572554546, 1),
	"members" : [
		{
			"_id" : 0,
			"name" : "member1:27017",
			"ip" : "172.31.26.121",
			"health" : 1,
			"state" : 2,
			"stateStr" : "SECONDARY",
			"uptime" : 764,
			"optime" : {
				"ts" : Timestamp(1572554586, 1),
				"t" : NumberLong(2)
			},
			"optimeDate" : ISODate("2019-10-31T20:43:06Z"),
			"syncingTo" : "member3:27017",
			"syncSourceHost" : "member3:27017",
			"syncSourceId" : 2,
			"infoMessage" : "",
			"configVersion" : 1,
			"self" : true,
			"lastHeartbeatMessage" : ""
		},
		{
			"_id" : 1,
			"name" : "member2:27017",
			"ip" : "172.31.29.144",
			"health" : 1,
			"state" : 1,
			"stateStr" : "PRIMARY",
			"uptime" : 762,
			"optime" : {
				"ts" : Timestamp(1572554586, 1),
				"t" : NumberLong(2)
			},
			"optimeDurable" : {
				"ts" : Timestamp(1572554586, 1),
				"t" : NumberLong(2)
			},
			"optimeDate" : ISODate("2019-10-31T20:43:06Z"),
			"optimeDurableDate" : ISODate("2019-10-31T20:43:06Z"),
			"lastHeartbeat" : ISODate("2019-10-31T20:43:11.005Z"),
			"lastHeartbeatRecv" : ISODate("2019-10-31T20:43:12.776Z"),
			"pingMs" : NumberLong(0),
			"lastHeartbeatMessage" : "",
			"syncingTo" : "",
			"syncSourceHost" : "",
			"syncSourceId" : -1,
			"infoMessage" : "",
			"electionTime" : Timestamp(1572552115, 1),
			"electionDate" : ISODate("2019-10-31T20:01:55Z"),
			"configVersion" : 1
		},
		{
			"_id" : 2,
			"name" : "member3:27017",
			"ip" : "172.31.21.18",
			"health" : 1,
			"state" : 2,
			"stateStr" : "SECONDARY",
			"uptime" : 762,
			"optime" : {
				"ts" : Timestamp(1572554586, 1),
				"t" : NumberLong(2)
			},
			"optimeDurable" : {
				"ts" : Timestamp(1572554586, 1),
				"t" : NumberLong(2)
			},
			"optimeDate" : ISODate("2019-10-31T20:43:06Z"),
			"optimeDurableDate" : ISODate("2019-10-31T20:43:06Z"),
			"lastHeartbeat" : ISODate("2019-10-31T20:43:11.005Z"),
			"lastHeartbeatRecv" : ISODate("2019-10-31T20:43:12.825Z"),
			"pingMs" : NumberLong(0),
			"lastHeartbeatMessage" : "",
			"syncingTo" : "member2:27017",
			"syncSourceHost" : "member2:27017",
			"syncSourceId" : 1,
			"infoMessage" : "",
			"configVersion" : 1
		}
	],
	"ok" : 1,
	"$clusterTime" : {
		"clusterTime" : Timestamp(1572554586, 1),
		"signature" : {
			"hash" : BinData(0,"AAAAAAAAAAAAAAAAAAAAAAAAAAA="),
			"keyId" : NumberLong(0)
		}
	},
	"operationTime" : Timestamp(1572554586, 1)
}


rs.config()
{
	"_id" : "rs0",
	"version" : 1,
	"protocolVersion" : NumberLong(1),
	"writeConcernMajorityJournalDefault" : true,
	"members" : [
		{
			"_id" : 0,
			"host" : "member1:27017",
			"arbiterOnly" : false,
			"buildIndexes" : true,
			"hidden" : false,
			"priority" : 1,
			"tags" : {
				
			},
			"slaveDelay" : NumberLong(0),
			"votes" : 1
		},
		{
			"_id" : 1,
			"host" : "member2:27017",
			"arbiterOnly" : false,
			"buildIndexes" : true,
			"hidden" : false,
			"priority" : 1,
			"tags" : {
				
			},
			"slaveDelay" : NumberLong(0),
			"votes" : 1
		},
		{
			"_id" : 2,
			"host" : "member3:27017",
			"arbiterOnly" : false,
			"buildIndexes" : true,
			"hidden" : false,
			"priority" : 1,
			"tags" : {
				
			},
			"slaveDelay" : NumberLong(0),
			"votes" : 1
		}
	],
	"settings" : {
		"chainingAllowed" : true,
		"heartbeatIntervalMillis" : 2000,
		"heartbeatTimeoutSecs" : 10,
		"electionTimeoutMillis" : 10000,
		"catchUpTimeoutMillis" : -1,
		"catchUpTakeoverDelayMillis" : 30000,
		"getLastErrorModes" : {
			
		},
		"getLastErrorDefaults" : {
			"w" : 1,
			"wtimeout" : 0
		},
		"replicaSetId" : ObjectId("5dbb2d102c0215827c9f6918")
	}
}

```


![alt text](https://github.com/kamel2700/DS_lab9/blob/master/Screenshot%20from%202019-10-31%2023-01-00.png)



```
rs.status()
{
	"set" : "rs0",
	"date" : ISODate("2019-10-31T20:53:23.524Z"),
	"myState" : 1,
	"term" : NumberLong(3),
	"syncingTo" : "",
	"syncSourceHost" : "",
	"syncSourceId" : -1,
	"heartbeatIntervalMillis" : NumberLong(2000),
	"majorityVoteCount" : 2,
	"writeMajorityCount" : 2,
	"optimes" : {
		"lastCommittedOpTime" : {
			"ts" : Timestamp(1572555202, 1),
			"t" : NumberLong(3)
		},
		"lastCommittedWallTime" : ISODate("2019-10-31T20:53:22.807Z"),
		"readConcernMajorityOpTime" : {
			"ts" : Timestamp(1572555202, 1),
			"t" : NumberLong(3)
		},
		"readConcernMajorityWallTime" : ISODate("2019-10-31T20:53:22.807Z"),
		"appliedOpTime" : {
			"ts" : Timestamp(1572555202, 1),
			"t" : NumberLong(3)
		},
		"durableOpTime" : {
			"ts" : Timestamp(1572555202, 1),
			"t" : NumberLong(3)
		},
		"lastAppliedWallTime" : ISODate("2019-10-31T20:53:22.807Z"),
		"lastDurableWallTime" : ISODate("2019-10-31T20:53:22.807Z")
	},
	"lastStableRecoveryTimestamp" : Timestamp(1572555142, 1),
	"lastStableCheckpointTimestamp" : Timestamp(1572555142, 1),
	"electionCandidateMetrics" : {
		"lastElectionReason" : "stepUpRequestSkipDryRun",
		"lastElectionDate" : ISODate("2019-10-31T20:49:02.777Z"),
		"termAtElection" : NumberLong(3),
		"lastCommittedOpTimeAtElection" : {
			"ts" : Timestamp(1572554936, 1),
			"t" : NumberLong(2)
		},
		"lastSeenOpTimeAtElection" : {
			"ts" : Timestamp(1572554936, 1),
			"t" : NumberLong(2)
		},
		"numVotesNeeded" : 2,
		"priorityAtElection" : 1,
		"electionTimeoutMillis" : NumberLong(10000),
		"priorPrimaryMemberId" : 1,
		"numCatchUpOps" : NumberLong(27017),
		"newTermStartDate" : ISODate("2019-10-31T20:49:02.799Z"),
		"wMajorityWriteAvailabilityDate" : ISODate("2019-10-31T20:49:03.279Z")
	},
	"members" : [
		{
			"_id" : 0,
			"name" : "member1:27017",
			"ip" : "172.31.26.121",
			"health" : 1,
			"state" : 1,
			"stateStr" : "PRIMARY",
			"uptime" : 1375,
			"optime" : {
				"ts" : Timestamp(1572555202, 1),
				"t" : NumberLong(3)
			},
			"optimeDate" : ISODate("2019-10-31T20:53:22Z"),
			"syncingTo" : "",
			"syncSourceHost" : "",
			"syncSourceId" : -1,
			"infoMessage" : "",
			"electionTime" : Timestamp(1572554942, 1),
			"electionDate" : ISODate("2019-10-31T20:49:02Z"),
			"configVersion" : 1,
			"self" : true,
			"lastHeartbeatMessage" : ""
		},
		{
			"_id" : 1,
			"name" : "member2:27017",
			"ip" : "172.31.29.144",
			"health" : 0,
			"state" : 8,
			"stateStr" : "(not reachable/healthy)",
			"uptime" : 0,
			"optime" : {
				"ts" : Timestamp(0, 0),
				"t" : NumberLong(-1)
			},
			"optimeDurable" : {
				"ts" : Timestamp(0, 0),
				"t" : NumberLong(-1)
			},
			"optimeDate" : ISODate("1970-01-01T00:00:00Z"),
			"optimeDurableDate" : ISODate("1970-01-01T00:00:00Z"),
			"lastHeartbeat" : ISODate("2019-10-31T20:53:21.437Z"),
			"lastHeartbeatRecv" : ISODate("2019-10-31T20:49:02.817Z"),
			"pingMs" : NumberLong(0),
			"lastHeartbeatMessage" : "Error connecting to member2:27017 (172.31.29.144:27017) :: caused by :: No route to host",
			"syncingTo" : "",
			"syncSourceHost" : "",
			"syncSourceId" : -1,
			"infoMessage" : "",
			"configVersion" : -1
		},
		{
			"_id" : 2,
			"name" : "member3:27017",
			"ip" : "172.31.21.18",
			"health" : 1,
			"state" : 2,
			"stateStr" : "SECONDARY",
			"uptime" : 1373,
			"optime" : {
				"ts" : Timestamp(1572555202, 1),
				"t" : NumberLong(3)
			},
			"optimeDurable" : {
				"ts" : Timestamp(1572555202, 1),
				"t" : NumberLong(3)
			},
			"optimeDate" : ISODate("2019-10-31T20:53:22Z"),
			"optimeDurableDate" : ISODate("2019-10-31T20:53:22Z"),
			"lastHeartbeat" : ISODate("2019-10-31T20:53:22.819Z"),
			"lastHeartbeatRecv" : ISODate("2019-10-31T20:53:22.886Z"),
			"pingMs" : NumberLong(0),
			"lastHeartbeatMessage" : "",
			"syncingTo" : "member1:27017",
			"syncSourceHost" : "member1:27017",
			"syncSourceId" : 0,
			"infoMessage" : "",
			"configVersion" : 1
		}
	],
	"ok" : 1,
	"$clusterTime" : {
		"clusterTime" : Timestamp(1572555202, 1),
		"signature" : {
			"hash" : BinData(0,"AAAAAAAAAAAAAAAAAAAAAAAAAAA="),
			"keyId" : NumberLong(0)
		}
	},
	"operationTime" : Timestamp(1572555202, 1)
}



rs.config()
{
	"_id" : "rs0",
	"version" : 1,
	"protocolVersion" : NumberLong(1),
	"writeConcernMajorityJournalDefault" : true,
	"members" : [
		{
			"_id" : 0,
			"host" : "member1:27017",
			"arbiterOnly" : false,
			"buildIndexes" : true,
			"hidden" : false,
			"priority" : 1,
			"tags" : {
				
			},
			"slaveDelay" : NumberLong(0),
			"votes" : 1
		},
		{
			"_id" : 1,
			"host" : "member2:27017",
			"arbiterOnly" : false,
			"buildIndexes" : true,
			"hidden" : false,
			"priority" : 1,
			"tags" : {
				
			},
			"slaveDelay" : NumberLong(0),
			"votes" : 1
		},
		{
			"_id" : 2,
			"host" : "member3:27017",
			"arbiterOnly" : false,
			"buildIndexes" : true,
			"hidden" : false,
			"priority" : 1,
			"tags" : {
				
			},
			"slaveDelay" : NumberLong(0),
			"votes" : 1
		}
	],
	"settings" : {
		"chainingAllowed" : true,
		"heartbeatIntervalMillis" : 2000,
		"heartbeatTimeoutSecs" : 10,
		"electionTimeoutMillis" : 10000,
		"catchUpTimeoutMillis" : -1,
		"catchUpTakeoverDelayMillis" : 30000,
		"getLastErrorModes" : {
			
		},
		"getLastErrorDefaults" : {
			"w" : 1,
			"wtimeout" : 0
		},
		"replicaSetId" : ObjectId("5dbb2d102c0215827c9f6918")
	}
}

```

![alt text](https://github.com/kamel2700/DS_lab9/blob/master/Screenshot%20from%202019-10-31%2023-09-18.png)
