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

```
