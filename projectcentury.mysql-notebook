{
    "type": "MySQLNotebook",
    "version": "1.0",
    "caption": "DB Notebook",
    "content": "\\about\nUSE viratkohli;\nSELECT COUNT(*) AS Total_Centuries\nFROM centuries;\nSELECT AVG(Runs) AS Average_Runs\nFROM centuries;\nSELECT Against, Runs, Venue, Ground, Date, Result\nFROM centuries\nORDER BY Runs DESC\nLIMIT 1;\n\nSELECT Against, COUNT(*) AS Centuries_Count\nFROM centuries\nGROUP BY Against;\n\nSELECT Venue, COUNT(*) AS Centuries_Count\nFROM centuries\nGROUP BY Venue;\n\nSELECT Result, COUNT(*) AS Match_Count\nFROM centuries\nGROUP BY Result;\n\n\nSELECT AVG(Position) AS Average_Batting_Position\nFROM centuries;\n\nSELECT COUNT(*) AS Away_Centuries\nFROM centuries\nWHERE Ground LIKE '%Away%';\n\nSELECT COUNT(*) AS Home_Centuries\nFROM centuries\nWHERE Ground LIKE '%Home%';\nSELECT \n    CASE \n        WHEN Ground LIKE '%Home%' THEN 'Home'\n        ELSE 'Away'\n    END AS Ground_Type,\n    COUNT(*) AS Centuries_Count\nFROM centuries\nGROUP BY Ground_Type;\n\n\n",
    "options": {
        "tabSize": 4,
        "indentSize": 4,
        "insertSpaces": true,
        "defaultEOL": "LF",
        "trimAutoWhitespace": true
    },
    "viewState": {
        "cursorState": [
            {
                "inSelectionMode": false,
                "selectionStart": {
                    "lineNumber": 45,
                    "column": 1
                },
                "position": {
                    "lineNumber": 45,
                    "column": 1
                }
            }
        ],
        "viewState": {
            "scrollLeft": 0,
            "firstPosition": {
                "lineNumber": 2,
                "column": 1
            },
            "firstPositionDeltaTop": 33
        },
        "contributionsState": {
            "editor.contrib.folding": {},
            "editor.contrib.wordHighlighter": false
        }
    },
    "contexts": [
        {
            "state": {
                "start": 1,
                "end": 1,
                "language": "mysql",
                "result": {
                    "type": "text",
                    "text": [
                        {
                            "type": 2,
                            "content": "Welcome to the MySQL Shell - DB Notebook.\n\nPress Ctrl+Enter to execute the code block.\n\nExecute \\sql to switch to SQL, \\js to JavaScript and \\ts to TypeScript mode.\nExecute \\help or \\? for help;",
                            "language": "ansi"
                        }
                    ]
                },
                "currentHeight": 118.390625,
                "statements": [
                    {
                        "delimiter": ";",
                        "span": {
                            "start": 0,
                            "length": 6
                        },
                        "contentStart": 0,
                        "state": 0
                    }
                ]
            },
            "data": []
        },
        {
            "state": {
                "start": 2,
                "end": 2,
                "language": "mysql",
                "result": {
                    "type": "text",
                    "text": [
                        {
                            "type": 4,
                            "index": 0,
                            "resultId": "71e41702-dc5b-4a82-a447-0b6bd73f251b",
                            "content": "OK, 0 records retrieved in 1.976ms"
                        }
                    ]
                },
                "currentHeight": 28,
                "statements": [
                    {
                        "delimiter": ";",
                        "span": {
                            "start": 0,
                            "length": 15
                        },
                        "contentStart": 0,
                        "state": 0
                    }
                ]
            },
            "data": []
        },
        {
            "state": {
                "start": 3,
                "end": 4,
                "language": "mysql",
                "result": {
                    "type": "resultIds",
                    "list": [
                        "0ecf64b8-3841-4dc5-9db8-f33d7f3b3f08"
                    ]
                },
                "currentHeight": 89.796875,
                "statements": [
                    {
                        "delimiter": ";",
                        "span": {
                            "start": 0,
                            "length": 50
                        },
                        "contentStart": 0,
                        "state": 0
                    }
                ]
            },
            "data": [
                {
                    "tabId": "363ca4de-6024-4e64-b18b-2abd488e7bb8",
                    "resultId": "0ecf64b8-3841-4dc5-9db8-f33d7f3b3f08",
                    "rows": [
                        {
                            "0": 80
                        }
                    ],
                    "columns": [
                        {
                            "title": "Total_Centuries",
                            "field": "0",
                            "dataType": {
                                "type": 4
                            }
                        }
                    ],
                    "executionInfo": {
                        "text": "OK, 1 record retrieved in 1.994ms"
                    },
                    "totalRowCount": 1,
                    "hasMoreRows": false,
                    "currentPage": 0,
                    "index": 0,
                    "sql": "SELECT COUNT(*) AS Total_Centuries\nFROM centuries"
                }
            ]
        },
        {
            "state": {
                "start": 5,
                "end": 6,
                "language": "mysql",
                "result": {
                    "type": "resultIds",
                    "list": [
                        "e7c1ba5c-f10c-470e-abd2-7d5fa44ebcb3"
                    ]
                },
                "currentHeight": 89.796875,
                "statements": [
                    {
                        "delimiter": ";",
                        "span": {
                            "start": 0,
                            "length": 48
                        },
                        "contentStart": 0,
                        "state": 0
                    },
                    {
                        "delimiter": ";",
                        "span": {
                            "start": 48,
                            "length": 0
                        },
                        "contentStart": 47,
                        "state": 3
                    }
                ]
            },
            "data": [
                {
                    "tabId": "363ca4de-6024-4e64-b18b-2abd488e7bb8",
                    "resultId": "e7c1ba5c-f10c-470e-abd2-7d5fa44ebcb3",
                    "rows": [
                        {
                            "0": 131.55
                        }
                    ],
                    "columns": [
                        {
                            "title": "Average_Runs",
                            "field": "0",
                            "dataType": {
                                "type": 9
                            }
                        }
                    ],
                    "executionInfo": {
                        "text": "OK, 1 record retrieved in 6.372ms"
                    },
                    "totalRowCount": 1,
                    "hasMoreRows": false,
                    "currentPage": 0,
                    "index": 0,
                    "sql": "SELECT AVG(Runs) AS Average_Runs\nFROM centuries"
                }
            ]
        },
        {
            "state": {
                "start": 7,
                "end": 11,
                "language": "mysql",
                "result": {
                    "type": "resultIds",
                    "list": [
                        "9e1ef0a4-7944-4cff-d5e3-6c0f0fe39086"
                    ]
                },
                "currentHeight": 152.1875,
                "statements": [
                    {
                        "delimiter": ";",
                        "span": {
                            "start": 0,
                            "length": 92
                        },
                        "contentStart": 0,
                        "state": 0
                    },
                    {
                        "delimiter": ";",
                        "span": {
                            "start": 92,
                            "length": 1
                        },
                        "contentStart": 91,
                        "state": 3
                    }
                ]
            },
            "data": [
                {
                    "tabId": "363ca4de-6024-4e64-b18b-2abd488e7bb8",
                    "resultId": "9e1ef0a4-7944-4cff-d5e3-6c0f0fe39086",
                    "rows": [
                        {
                            "0": "South Africa",
                            "1": "254*",
                            "2": "Maharashtra Cricket Association Stadium, Pune",
                            "3": "Home",
                            "4": "10-Oct-19",
                            "5": "Won"
                        }
                    ],
                    "columns": [
                        {
                            "title": "Against",
                            "field": "0",
                            "dataType": {
                                "type": 17
                            }
                        },
                        {
                            "title": "Runs",
                            "field": "1",
                            "dataType": {
                                "type": 17
                            }
                        },
                        {
                            "title": "Venue",
                            "field": "2",
                            "dataType": {
                                "type": 17
                            }
                        },
                        {
                            "title": "Ground",
                            "field": "3",
                            "dataType": {
                                "type": 17
                            }
                        },
                        {
                            "title": "Date",
                            "field": "4",
                            "dataType": {
                                "type": 17
                            }
                        },
                        {
                            "title": "Result",
                            "field": "5",
                            "dataType": {
                                "type": 17
                            }
                        }
                    ],
                    "executionInfo": {
                        "text": "OK, 1 record retrieved in 1.038ms"
                    },
                    "totalRowCount": 1,
                    "hasMoreRows": false,
                    "currentPage": 0,
                    "index": 0,
                    "sql": "SELECT Against, Runs, Venue, Ground, Date, Result\nFROM centuries\nORDER BY Runs DESC\nLIMIT 1"
                }
            ]
        },
        {
            "state": {
                "start": 12,
                "end": 15,
                "language": "mysql",
                "result": {
                    "type": "resultIds",
                    "list": [
                        "b24f0e8c-bf60-4b0b-aafc-0d3b0e4a4c53"
                    ]
                },
                "currentHeight": 36,
                "statements": [
                    {
                        "delimiter": ";",
                        "span": {
                            "start": 0,
                            "length": 76
                        },
                        "contentStart": 0,
                        "state": 0
                    },
                    {
                        "delimiter": ";",
                        "span": {
                            "start": 76,
                            "length": 1
                        },
                        "contentStart": 75,
                        "state": 3
                    }
                ]
            },
            "data": [
                {
                    "tabId": "363ca4de-6024-4e64-b18b-2abd488e7bb8",
                    "resultId": "b24f0e8c-bf60-4b0b-aafc-0d3b0e4a4c53",
                    "rows": [
                        {
                            "0": "Sri Lanka",
                            "1": 15
                        },
                        {
                            "0": "Bangladesh",
                            "1": 7
                        },
                        {
                            "0": "Australia",
                            "1": 16
                        },
                        {
                            "0": "New Zealand",
                            "1": 9
                        },
                        {
                            "0": "England",
                            "1": 8
                        },
                        {
                            "0": "West Indies",
                            "1": 12
                        },
                        {
                            "0": "Pakistan",
                            "1": 3
                        },
                        {
                            "0": "Zimbabwe",
                            "1": 1
                        },
                        {
                            "0": "South Africa",
                            "1": 8
                        },
                        {
                            "0": "Afghanistan",
                            "1": 1
                        }
                    ],
                    "columns": [
                        {
                            "title": "Against",
                            "field": "0",
                            "dataType": {
                                "type": 17
                            }
                        },
                        {
                            "title": "Centuries_Count",
                            "field": "1",
                            "dataType": {
                                "type": 4
                            }
                        }
                    ],
                    "executionInfo": {
                        "text": "OK, 10 records retrieved in 2.027ms"
                    },
                    "totalRowCount": 10,
                    "hasMoreRows": false,
                    "currentPage": 0,
                    "index": 0,
                    "sql": "SELECT Against, COUNT(*) AS Centuries_Count\nFROM centuries\nGROUP BY Against"
                }
            ]
        },
        {
            "state": {
                "start": 16,
                "end": 19,
                "language": "mysql",
                "result": {
                    "type": "resultIds",
                    "list": [
                        "68a59f25-487d-4c06-a8e2-95441d610772"
                    ]
                },
                "currentHeight": 36,
                "statements": [
                    {
                        "delimiter": ";",
                        "span": {
                            "start": 0,
                            "length": 72
                        },
                        "contentStart": 0,
                        "state": 0
                    },
                    {
                        "delimiter": ";",
                        "span": {
                            "start": 72,
                            "length": 1
                        },
                        "contentStart": 71,
                        "state": 3
                    }
                ]
            },
            "data": [
                {
                    "tabId": "363ca4de-6024-4e64-b18b-2abd488e7bb8",
                    "resultId": "68a59f25-487d-4c06-a8e2-95441d610772",
                    "rows": [
                        {
                            "0": "Eden Gardens, Kolkata",
                            "1": 4
                        },
                        {
                            "0": "Sher-e-Bangla Cricket Stadium, Dhaka",
                            "1": 4
                        },
                        {
                            "0": "APCA-VDCA Stadium, Visakhapatnam",
                            "1": 2
                        },
                        {
                            "0": "Nehru Stadium, Guwahati",
                            "1": 1
                        },
                        {
                            "0": "Sophia Gardens, Cardiff",
                            "1": 1
                        },
                        {
                            "0": "Feroz Shah Kotla Ground, Delhi",
                            "1": 2
                        },
                        {
                            "0": "Adelaide Oval, Adelaide",
                            "1": 5
                        },
                        {
                            "0": "Bellerive Oval, Hobart",
                            "1": 1
                        },
                        {
                            "0": "MRIC Stadium, Hambantota",
                            "1": 1
                        },
                        {
                            "0": "R. Premadasa Stadium, Colombo",
                            "1": 4
                        },
                        {
                            "0": "M. Chinnaswamy Stadium, Bangalore",
                            "1": 1
                        },
                        {
                            "0": "Vidarbha Cricket Association Stadium, Nagpur",
                            "1": 3
                        },
                        {
                            "0": "M. A. Chidambaram Stadium, Chennai",
                            "1": 2
                        },
                        {
                            "0": "Queen's Park Oval, Port of Spain",
                            "1": 4
                        },
                        {
                            "0": "Harare Sports Club, Harare",
                            "1": 1
                        },
                        {
                            "0": "Sawai Mansingh Stadium, Jaipur",
                            "1": 1
                        },
                        {
                            "0": "VCA Stadium, Nagpur",
                            "1": 1
                        },
                        {
                            "0": "Wanderers Stadium, Johannesburg",
                            "1": 1
                        },
                        {
                            "0": "McLean Park, Napier",
                            "1": 1
                        },
                        {
                            "0": "Basin Reserve, Wellington",
                            "1": 1
                        },
                        {
                            "0": "Khan Shaheb Osman Ali Stadium, Fatullah",
                            "1": 1
                        },
                        {
                            "0": "HPCA Stadium, Dharamshala",
                            "1": 1
                        },
                        {
                            "0": "JSCA International Stadium, Ranchi",
                            "1": 2
                        },
                        {
                            "0": "Melbourne Cricket Ground, Melbourne",
                            "1": 2
                        },
                        {
                            "0": "Sydney Cricket Ground, Sydney",
                            "1": 1
                        },
                        {
                            "0": "Galle International Stadium, Galle",
                            "1": 2
                        },
                        {
                            "0": "Manuka Oval, Canberra",
                            "1": 1
                        },
                        {
                            "0": "Sir Vivian Richards Stadium, North Sound",
                            "1": 1
                        },
                        {
                            "0": "Holkar Stadium, Indore",
                            "1": 1
                        },
                        {
                            "0": "Punjab Cricket Association IS Bindra Stadium, Mohali",
                            "1": 1
                        },
                        {
                            "0": "ACA-VDCA Cricket Stadium, Visakhapatnam",
                            "1": 2
                        },
                        {
                            "0": "Wankhede Stadium, Mumbai",
                            "1": 3
                        },
                        {
                            "0": "Maharashtra Cricket Association Stadium, Pune",
                            "1": 4
                        },
                        {
                            "0": "Rajiv Gandhi International Cricket Stadium, Hyderabad",
                            "1": 1
                        },
                        {
                            "0": "Sabina Park, Kingston",
                            "1": 1
                        },
                        {
                            "0": "Green Park Stadium, Kanpur",
                            "1": 1
                        },
                        {
                            "0": "SuperSport Park, Centurion",
                            "1": 2
                        },
                        {
                            "0": "Kingsmead Cricket Ground, Durban",
                            "1": 1
                        },
                        {
                            "0": "Newlands Cricket Ground, Cape Town",
                            "1": 1
                        },
                        {
                            "0": "Edgbaston Cricket Ground, Birmingham",
                            "1": 1
                        },
                        {
                            "0": "Trent Bridge, Nottingham",
                            "1": 1
                        },
                        {
                            "0": "Saurashtra Cricket Association Stadium, Rajkot",
                            "1": 1
                        },
                        {
                            "0": "ACA Stadium, Guwahati",
                            "1": 2
                        },
                        {
                            "0": "Perth Stadium, Perth",
                            "1": 1
                        },
                        {
                            "0": "Dubai International Cricket Stadium, Dubai",
                            "1": 1
                        },
                        {
                            "0": "Zohur Ahmed Chowdhury Stadium, Chittagong",
                            "1": 1
                        },
                        {
                            "0": "Greenfield International Stadium, Thiruvananthapuram",
                            "1": 1
                        },
                        {
                            "0": "Narendra Modi Stadium, Ahmedabad",
                            "1": 1
                        }
                    ],
                    "columns": [
                        {
                            "title": "Venue",
                            "field": "0",
                            "dataType": {
                                "type": 17
                            }
                        },
                        {
                            "title": "Centuries_Count",
                            "field": "1",
                            "dataType": {
                                "type": 4
                            }
                        }
                    ],
                    "executionInfo": {
                        "text": "OK, 48 records retrieved in 0.998ms"
                    },
                    "totalRowCount": 48,
                    "hasMoreRows": false,
                    "currentPage": 0,
                    "index": 0,
                    "sql": "SELECT Venue, COUNT(*) AS Centuries_Count\nFROM centuries\nGROUP BY Venue"
                }
            ]
        },
        {
            "state": {
                "start": 20,
                "end": 24,
                "language": "mysql",
                "result": {
                    "type": "resultIds",
                    "list": [
                        "ed188a1c-21de-41eb-b6d2-138d9e15ef6c"
                    ]
                },
                "currentHeight": 36,
                "statements": [
                    {
                        "delimiter": ";",
                        "span": {
                            "start": 0,
                            "length": 70
                        },
                        "contentStart": 0,
                        "state": 0
                    },
                    {
                        "delimiter": ";",
                        "span": {
                            "start": 70,
                            "length": 2
                        },
                        "contentStart": 69,
                        "state": 3
                    }
                ]
            },
            "data": [
                {
                    "tabId": "363ca4de-6024-4e64-b18b-2abd488e7bb8",
                    "resultId": "ed188a1c-21de-41eb-b6d2-138d9e15ef6c",
                    "rows": [
                        {
                            "0": "Won",
                            "1": 55
                        },
                        {
                            "0": "Lost (D/L)",
                            "1": 1
                        },
                        {
                            "0": "Lost",
                            "1": 13
                        },
                        {
                            "0": "Drawn",
                            "1": 9
                        },
                        {
                            "0": "Won (D/L)",
                            "1": 1
                        },
                        {
                            "0": "Tied",
                            "1": 1
                        }
                    ],
                    "columns": [
                        {
                            "title": "Result",
                            "field": "0",
                            "dataType": {
                                "type": 17
                            }
                        },
                        {
                            "title": "Match_Count",
                            "field": "1",
                            "dataType": {
                                "type": 4
                            }
                        }
                    ],
                    "executionInfo": {
                        "text": "OK, 6 records retrieved in 0.956ms"
                    },
                    "totalRowCount": 6,
                    "hasMoreRows": false,
                    "currentPage": 0,
                    "index": 0,
                    "sql": "SELECT Result, COUNT(*) AS Match_Count\nFROM centuries\nGROUP BY Result"
                }
            ]
        },
        {
            "state": {
                "start": 25,
                "end": 27,
                "language": "mysql",
                "result": {
                    "type": "resultIds",
                    "list": [
                        "1f114029-5a38-4669-e8c1-d7c5b0faab39"
                    ]
                },
                "currentHeight": 36,
                "statements": [
                    {
                        "delimiter": ";",
                        "span": {
                            "start": 0,
                            "length": 64
                        },
                        "contentStart": 0,
                        "state": 0
                    },
                    {
                        "delimiter": ";",
                        "span": {
                            "start": 64,
                            "length": 1
                        },
                        "contentStart": 63,
                        "state": 3
                    }
                ]
            },
            "data": [
                {
                    "tabId": "363ca4de-6024-4e64-b18b-2abd488e7bb8",
                    "resultId": "1f114029-5a38-4669-e8c1-d7c5b0faab39",
                    "rows": [
                        {
                            "0": "3.5000"
                        }
                    ],
                    "columns": [
                        {
                            "title": "Average_Batting_Position",
                            "field": "0",
                            "dataType": {
                                "type": 10
                            }
                        }
                    ],
                    "executionInfo": {
                        "text": "OK, 1 record retrieved in 0.956ms"
                    },
                    "totalRowCount": 1,
                    "hasMoreRows": false,
                    "currentPage": 0,
                    "index": 0,
                    "sql": "SELECT AVG(Position) AS Average_Batting_Position\nFROM centuries"
                }
            ]
        },
        {
            "state": {
                "start": 28,
                "end": 31,
                "language": "mysql",
                "result": {
                    "type": "resultIds",
                    "list": [
                        "1d68bb50-5487-4271-9d90-673a6e8d631b"
                    ]
                },
                "currentHeight": 36,
                "statements": [
                    {
                        "delimiter": ";",
                        "span": {
                            "start": 0,
                            "length": 76
                        },
                        "contentStart": 0,
                        "state": 0
                    },
                    {
                        "delimiter": ";",
                        "span": {
                            "start": 76,
                            "length": 1
                        },
                        "contentStart": 75,
                        "state": 3
                    }
                ]
            },
            "data": [
                {
                    "tabId": "363ca4de-6024-4e64-b18b-2abd488e7bb8",
                    "resultId": "1d68bb50-5487-4271-9d90-673a6e8d631b",
                    "rows": [
                        {
                            "0": 36
                        }
                    ],
                    "columns": [
                        {
                            "title": "Away_Centuries",
                            "field": "0",
                            "dataType": {
                                "type": 4
                            }
                        }
                    ],
                    "executionInfo": {
                        "text": "OK, 1 record retrieved in 0.996ms"
                    },
                    "totalRowCount": 1,
                    "hasMoreRows": false,
                    "currentPage": 0,
                    "index": 0,
                    "sql": "SELECT COUNT(*) AS Away_Centuries\nFROM centuries\nWHERE Ground LIKE '%Away%'"
                }
            ]
        },
        {
            "state": {
                "start": 32,
                "end": 34,
                "language": "mysql",
                "result": {
                    "type": "resultIds",
                    "list": [
                        "094583aa-ae24-41e4-eaa1-18c3b8fe99a7"
                    ]
                },
                "currentHeight": 36,
                "statements": [
                    {
                        "delimiter": ";",
                        "span": {
                            "start": 0,
                            "length": 76
                        },
                        "contentStart": 0,
                        "state": 0
                    }
                ]
            },
            "data": [
                {
                    "tabId": "363ca4de-6024-4e64-b18b-2abd488e7bb8",
                    "resultId": "094583aa-ae24-41e4-eaa1-18c3b8fe99a7",
                    "rows": [
                        {
                            "0": 38
                        }
                    ],
                    "columns": [
                        {
                            "title": "Home_Centuries",
                            "field": "0",
                            "dataType": {
                                "type": 4
                            }
                        }
                    ],
                    "executionInfo": {
                        "text": "OK, 1 record retrieved in 0.993ms"
                    },
                    "totalRowCount": 1,
                    "hasMoreRows": false,
                    "currentPage": 0,
                    "index": 0,
                    "sql": "SELECT COUNT(*) AS Home_Centuries\nFROM centuries\nWHERE Ground LIKE '%Home%'"
                }
            ]
        },
        {
            "state": {
                "start": 35,
                "end": 44,
                "language": "mysql",
                "result": {
                    "type": "resultIds",
                    "list": [
                        "ca726729-ebcb-4dbe-83fd-27f1828dfacd"
                    ]
                },
                "currentHeight": 36,
                "statements": [
                    {
                        "delimiter": ";",
                        "span": {
                            "start": 0,
                            "length": 176
                        },
                        "contentStart": 0,
                        "state": 0
                    },
                    {
                        "delimiter": ";",
                        "span": {
                            "start": 176,
                            "length": 2
                        },
                        "contentStart": 175,
                        "state": 3
                    }
                ]
            },
            "data": [
                {
                    "tabId": "363ca4de-6024-4e64-b18b-2abd488e7bb8",
                    "resultId": "ca726729-ebcb-4dbe-83fd-27f1828dfacd",
                    "rows": [
                        {
                            "0": "Home",
                            "1": 38
                        },
                        {
                            "0": "Away",
                            "1": 42
                        }
                    ],
                    "columns": [
                        {
                            "title": "Ground_Type",
                            "field": "0",
                            "dataType": {
                                "type": 17
                            }
                        },
                        {
                            "title": "Centuries_Count",
                            "field": "1",
                            "dataType": {
                                "type": 4
                            }
                        }
                    ],
                    "executionInfo": {
                        "text": "OK, 2 records retrieved in 0.955ms"
                    },
                    "totalRowCount": 2,
                    "hasMoreRows": false,
                    "currentPage": 0,
                    "index": 0,
                    "sql": "SELECT \n    CASE \n        WHEN Ground LIKE '%Home%' THEN 'Home'\n        ELSE 'Away'\n    END AS Ground_Type,\n    COUNT(*) AS Centuries_Count\nFROM centuries\nGROUP BY Ground_Type"
                }
            ]
        },
        {
            "state": {
                "start": 45,
                "end": 45,
                "language": "mysql",
                "currentHeight": 180,
                "statements": [
                    {
                        "delimiter": ";",
                        "span": {
                            "start": 0,
                            "length": 0
                        },
                        "contentStart": 0,
                        "state": 0
                    }
                ]
            },
            "data": []
        }
    ]
}