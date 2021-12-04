{
  "branches": {
    "main": {
      "remoteTrackingBranchID": null,
      "remote": false,
      "target": "C3",
      "id": "main",
      "type": "branch"
    },
    "bugFix": {
      "remoteTrackingBranchID": null,
      "remote": false,
      "target": "C2'",
      "id": "bugFix",
      "type": "branch"
    }
  },
  "commits": {
    "C0": {
      "type": "commit",
      "parents": [],
      "author": "Peter Cottle",
      "createTime": "Mon Nov 05 2012 00:56:47 GMT-0800 (PST)",
      "commitMessage": "Quick Commit. Go Bears!",
      "id": "C0",
      "rootCommit": true
    },
    "C1": {
      "type": "commit",
      "parents": [
        "C0"
      ],
      "author": "Peter Cottle",
      "createTime": "Mon Nov 05 2012 00:56:47 GMT-0800 (PST)",
      "commitMessage": "Quick Commit. Go Bears!",
      "id": "C1"
    },
    "C2": {
      "type": "commit",
      "parents": [
        "C1"
      ],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 10:21:11 GMT+0300 (Москва, стандартное время)",
      "commitMessage": "Быстрый коммит. А надо!",
      "id": "C2"
    },
    "C3": {
      "type": "commit",
      "parents": [
        "C1"
      ],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 10:21:26 GMT+0300 (Москва, стандартное время)",
      "commitMessage": "Быстрый коммит. А надо!",
      "id": "C3"
    },
    "C2'": {
      "type": "commit",
      "parents": [
        "C3"
      ],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 10:21:45 GMT+0300 (Москва, стандартное время)",
      "commitMessage": "Быстрый коммит. А надо!",
      "id": "C2'"
    }
  },
  "tags": {},
  "HEAD": {
    "id": "HEAD",
    "target": "bugFix",
    "type": "general ref"
  }
}
