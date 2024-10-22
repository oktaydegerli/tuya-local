{
        "name": "Sigmesh Gateway",
        "id": "bf35b235c22774d615tc03",
        "key": "ji)xPdmx(?5x2n}/",
        "mac": "38:2c:e5:23:35:8f",
        "uuid": "c97ab31782934475",
        "sn": "100159734003C9",
        "category": "wg2",
        "product_name": "mesh\u7f51\u5173 CR3L",
        "product_id": "nowfshuifqwzudwr",
        "biz_type": 18,
        "model": "JMWBG1",
        "sub": true,
        "icon": "https://images.tuyaeu.com/smart/icon/ay1562803410690AUgvL/165491159782534db9e4c.png",
        "mapping": {},
        "parent": "",
        "ip": "192.168.1.49",
        "version": "3.4"
    },
    {
        "name": "Access Control",
        "id": "bf54b2fenmpbujea",
        "key": "ji)xPdmx(?5x2n}/",
        "mac": "DC:23:4F:99:99:F0",
        "uuid": "uuidfd468055bfc7",
        "category": "jtmspro",
        "product_name": "\u84dd\u7259\u667a\u80fd\u95e8\u7981",
        "product_id": "hq8p0gzw",
        "biz_type": 18,
        "model": "TF9",
        "sub": true,
        "icon": "https://images.tuyaeu.com/smart/icon/bay16665820988057AGv/3937f1789a8a52b2dc9ab0e31be0600d.jpg",
        "node_id": "uuidfd468055bfc7",
        "mapping": {
            "1": {
                "code": "unlock_method_create",
                "type": "Raw",
                "values": {}
            },
            "2": {
                "code": "unlock_method_delete",
                "type": "Raw",
                "values": {}
            },
            "3": {
                "code": "unlock_method_modify",
                "type": "Raw",
                "values": {}
            },
            "12": {
                "code": "unlock_fingerprint",
                "type": "Integer",
                "values": {
                    "min": 0,
                    "max": 999,
                    "scale": 0,
                    "step": 1
                }
            },
            "13": {
                "code": "unlock_password",
                "type": "Integer",
                "values": {
                    "min": 0,
                    "max": 999,
                    "scale": 0,
                    "step": 1
                }
            },
            "14": {
                "code": "unlock_dynamic",
                "type": "Integer",
                "values": {
                    "min": 0,
                    "max": 999,
                    "scale": 0,
                    "step": 1
                }
            },
            "15": {
                "code": "unlock_card",
                "type": "Integer",
                "values": {
                    "min": 0,
                    "max": 999,
                    "scale": 0,
                    "step": 1
                }
            },
            "19": {
                "code": "unlock_ble",
                "type": "Integer",
                "values": {
                    "min": 0,
                    "max": 999,
                    "scale": 0,
                    "step": 1
                }
            },
            "28": {
                "code": "language",
                "type": "Enum",
                "values": {
                    "range": [
                        "chinese_simplified",
                        "english",
                        "japanese",
                        "german",
                        "spanish",
                        "latin",
                        "french",
                        "russian",
                        "italian",
                        "chinese_traditional",
                        "korean"
                    ]
                }
            },
            "31": {
                "code": "beep_volume",
                "type": "Enum",
                "values": {
                    "range": [
                        "mute",
                        "low",
                        "normal",
                        "high"
                    ]
                }
            },
            "33": {
                "code": "automatic_lock",
                "type": "Boolean",
                "values": {}
            },
            "36": {
                "code": "auto_lock_time",
                "type": "Integer",
                "values": {
                    "min": 1,
                    "max": 1800,
                    "scale": 0,
                    "step": 1
                }
            },
            "44": {
                "code": "rtc_lock",
                "type": "Boolean",
                "values": {}
            },
            "54": {
                "code": "synch_method",
                "type": "Raw",
                "values": {}
            },
            "70": {
                "code": "check_code_set",
                "type": "Raw",
                "values": {}
            },
            "71": {
                "code": "ble_unlock_check",
                "type": "Raw",
                "values": {}
            }
        },
        "parent": "bf35b235c22774d615tc03",
        "ip": "",
        "version": ""
    },
