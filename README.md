# DS_lab9



![alt text](https://github.com/kamel2700/DS_lab9/blob/master/Screenshot%20from%202019-10-31%2023-01-00.png)
rs.status()
{
	"set" : "rs0",
	"date" : ISODate("2019-10-31T19:59:39.262Z"),
	"myState" : 1,
	"term" : NumberLong(1),
	"syncingTo" : "",
	"syncSourceHost" : "",
	"syncSourceId" : -1,
	"heartbeatIntervalMillis" : NumberLong(2000),
	"majorityVoteCount" : 2,
	"writeMajorityCount" : 2,
	"optimes" : {
		"lastCommittedOpTime" : {
			"ts" : Timestamp(1572551977, 1),
			"t" : NumberLong(1)
		},
		"lastCommittedWallTime" : ISODate("2019-10-31T19:59:37.067Z"),
		"readConcernMajorityOpTime" : {
			"ts" : Timestamp(1572551977, 1),
			"t" : NumberLong(1)
		},
		"readConcernMajorityWallTime" : ISODate("2019-10-31T19:59:37.067Z"),
		"appliedOpTime" : {
			"ts" : Timestamp(1572551977, 1),
			"t" : NumberLong(1)
		},
		"durableOpTime" : {
			"ts" : Timestamp(1572551977, 1),
			"t" : NumberLong(1)
		},
		"lastAppliedWallTime" : ISODate("2019-10-31T19:59:37.067Z"),
		"lastDurableWallTime" : ISODate("2019-10-31T19:59:37.067Z")
	},
	"lastStableRecoveryTimestamp" : Timestamp(1572551947, 1),
	"lastStableCheckpointTimestamp" : Timestamp(1572551947, 1),
	"electionCandidateMetrics" : {
		"lastElectionReason" : "electionTimeout",
		"lastElectionDate" : ISODate("2019-10-31T18:51:07.266Z"),
		"termAtElection" : NumberLong(1),
		"lastCommittedOpTimeAtElection" : {
			"ts" : Timestamp(0, 0),
			"t" : NumberLong(-1)
		},
		"lastSeenOpTimeAtElection" : {
			"ts" : Timestamp(1572547856, 1),
			"t" : NumberLong(-1)
		},
		"numVotesNeeded" : 2,
		"priorityAtElection" : 1,
		"electionTimeoutMillis" : NumberLong(10000),
		"numCatchUpOps" : NumberLong(27017),
		"newTermStartDate" : ISODate("2019-10-31T18:51:07.573Z"),
		"wMajorityWriteAvailabilityDate" : ISODate("2019-10-31T18:51:08.230Z")
	},
	"members" : [
		{
			"_id" : 0,
			"name" : "member1:27017",
			"ip" : "172.31.26.121",
			"health" : 1,
			"state" : 1,
			"stateStr" : "PRIMARY",
			"uptime" : 4504,
			"optime" : {
				"ts" : Timestamp(1572551977, 1),
				"t" : NumberLong(1)
			},
			"optimeDate" : ISODate("2019-10-31T19:59:37Z"),
			"syncingTo" : "",
			"syncSourceHost" : "",
			"syncSourceId" : -1,
			"infoMessage" : "",
			"electionTime" : Timestamp(1572547867, 1),
			"electionDate" : ISODate("2019-10-31T18:51:07Z"),
			"configVersion" : 1,
			"self" : true,
			"lastHeartbeatMessage" : ""
		},
		{
			"_id" : 1,
			"name" : "member2:27017",
			"ip" : "172.31.29.144",
			"health" : 1,
			"state" : 2,
			"stateStr" : "SECONDARY",
			"uptime" : 4122,
			"optime" : {
				"ts" : Timestamp(1572551977, 1),
				"t" : NumberLong(1)
			},
			"optimeDurable" : {
				"ts" : Timestamp(1572551977, 1),
				"t" : NumberLong(1)
			},
			"optimeDate" : ISODate("2019-10-31T19:59:37Z"),
			"optimeDurableDate" : ISODate("2019-10-31T19:59:37Z"),
			"lastHeartbeat" : ISODate("2019-10-31T19:59:38.680Z"),
			"lastHeartbeatRecv" : ISODate("2019-10-31T19:59:38.680Z"),
			"pingMs" : NumberLong(0),
			"lastHeartbeatMessage" : "",
			"syncingTo" : "member1:27017",
			"syncSourceHost" : "member1:27017",
			"syncSourceId" : 0,
			"infoMessage" : "",
			"configVersion" : 1
		},
		{
			"_id" : 2,
			"name" : "member3:27017",
			"ip" : "172.31.21.18",
			"health" : 1,
			"state" : 2,
			"stateStr" : "SECONDARY",
			"uptime" : 4122,
			"optime" : {
				"ts" : Timestamp(1572551977, 1),
				"t" : NumberLong(1)
			},
			"optimeDurable" : {
				"ts" : Timestamp(1572551977, 1),
				"t" : NumberLong(1)
			},
			"optimeDate" : ISODate("2019-10-31T19:59:37Z"),
			"optimeDurableDate" : ISODate("2019-10-31T19:59:37Z"),
			"lastHeartbeat" : ISODate("2019-10-31T19:59:38.679Z"),
			"lastHeartbeatRecv" : ISODate("2019-10-31T19:59:38.679Z"),
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
		"clusterTime" : Timestamp(1572551977, 1),
		"signature" : {
			"hash" : BinData(0,"AAAAAAAAAAAAAAAAAAAAAAAAAAA="),
			"keyId" : NumberLong(0)
		}
	},
	"operationTime" : Timestamp(1572551977, 1)
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




![alt text](https://github.com/kamel2700/DS_lab9/blob/master/Screenshot%20from%202019-10-31%2023-09-18.png)



rs.status()
{
	"set" : "rs0",
	"date" : ISODate("2019-10-31T20:10:13.544Z"),
	"myState" : 1,
	"term" : NumberLong(2),
	"syncingTo" : "",
	"syncSourceHost" : "",
	"syncSourceId" : -1,
	"heartbeatIntervalMillis" : NumberLong(2000),
	"majorityVoteCount" : 2,
	"writeMajorityCount" : 2,
	"optimes" : {
		"lastCommittedOpTime" : {
			"ts" : Timestamp(1572552606, 1),
			"t" : NumberLong(2)
		},
		"lastCommittedWallTime" : ISODate("2019-10-31T20:10:06.733Z"),
		"readConcernMajorityOpTime" : {
			"ts" : Timestamp(1572552606, 1),
			"t" : NumberLong(2)
		},
		"readConcernMajorityWallTime" : ISODate("2019-10-31T20:10:06.733Z"),
		"appliedOpTime" : {
			"ts" : Timestamp(1572552606, 1),
			"t" : NumberLong(2)
		},
		"durableOpTime" : {
			"ts" : Timestamp(1572552606, 1),
			"t" : NumberLong(2)
		},
		"lastAppliedWallTime" : ISODate("2019-10-31T20:10:06.733Z"),
		"lastDurableWallTime" : ISODate("2019-10-31T20:10:06.733Z")
	},
	"lastStableRecoveryTimestamp" : Timestamp(1572552606, 1),
	"lastStableCheckpointTimestamp" : Timestamp(1572552606, 1),
	"electionCandidateMetrics" : {
		"lastElectionReason" : "stepUpRequestSkipDryRun",
		"lastElectionDate" : ISODate("2019-10-31T20:01:55.841Z"),
		"termAtElection" : NumberLong(2),
		"lastCommittedOpTimeAtElection" : {
			"ts" : Timestamp(1572552107, 1),
			"t" : NumberLong(1)
		},
		"lastSeenOpTimeAtElection" : {
			"ts" : Timestamp(1572552107, 1),
			"t" : NumberLong(1)
		},
		"numVotesNeeded" : 2,
		"priorityAtElection" : 1,
		"electionTimeoutMillis" : NumberLong(10000),
		"priorPrimaryMemberId" : 0,
		"numCatchUpOps" : NumberLong(27017),
		"newTermStartDate" : ISODate("2019-10-31T20:01:56.717Z"),
		"wMajorityWriteAvailabilityDate" : ISODate("2019-10-31T20:01:57.240Z")
	},
	"members" : [
		{
			"_id" : 0,
			"name" : "member1:27017",
			"ip" : "172.31.26.121",
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
			"lastHeartbeat" : ISODate("2019-10-31T20:10:13.137Z"),
			"lastHeartbeatRecv" : ISODate("2019-10-31T20:01:54.678Z"),
			"pingMs" : NumberLong(0),
			"lastHeartbeatMessage" : "Error connecting to member1:27017 (172.31.26.121:27017) :: caused by :: No route to host",
			"syncingTo" : "",
			"syncSourceHost" : "",
			"syncSourceId" : -1,
			"infoMessage" : "",
			"configVersion" : -1
		},
		{
			"_id" : 1,
			"name" : "member2:27017",
			"ip" : "172.31.29.144",
			"health" : 1,
			"state" : 1,
			"stateStr" : "PRIMARY",
			"uptime" : 4867,
			"optime" : {
				"ts" : Timestamp(1572552606, 1),
				"t" : NumberLong(2)
			},
			"optimeDate" : ISODate("2019-10-31T20:10:06Z"),
			"syncingTo" : "",
			"syncSourceHost" : "",
			"syncSourceId" : -1,
			"infoMessage" : "",
			"electionTime" : Timestamp(1572552115, 1),
			"electionDate" : ISODate("2019-10-31T20:01:55Z"),
			"configVersion" : 1,
			"self" : true,
			"lastHeartbeatMessage" : ""
		},
		{
			"_id" : 2,
			"name" : "member3:27017",
			"ip" : "172.31.21.18",
			"health" : 1,
			"state" : 2,
			"stateStr" : "SECONDARY",
			"uptime" : 4756,
			"optime" : {
				"ts" : Timestamp(1572552606, 1),
				"t" : NumberLong(2)
			},
			"optimeDurable" : {
				"ts" : Timestamp(1572552606, 1),
				"t" : NumberLong(2)
			},
			"optimeDate" : ISODate("2019-10-31T20:10:06Z"),
			"optimeDurableDate" : ISODate("2019-10-31T20:10:06Z"),
			"lastHeartbeat" : ISODate("2019-10-31T20:10:11.917Z"),
			"lastHeartbeatRecv" : ISODate("2019-10-31T20:10:13.335Z"),
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
		"clusterTime" : Timestamp(1572552606, 1),
		"signature" : {
			"hash" : BinData(0,"AAAAAAAAAAAAAAAAAAAAAAAAAAA="),
			"keyId" : NumberLong(0)
		}
	},
	"operationTime" : Timestamp(1572552606, 1)
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





