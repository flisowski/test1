"reason": {
			"title": "reason",
			"properties": {
				"description_identifier": {
					"description": "An enumeration type that provides the description for the reason of disqualification.",
					"type": "string",
					"notes": "For enumeration descriptions see `description_identifier` section in the [enumeration mappings](https://github.com/companieshouse/api-enumerations/blob/master/disqualified_officer_descriptions.yml)"
				},
				"act": {
					"description": "An enumeration type that provides the law under which the disqualification was made.",
					"type": "string",
					"notes": "For enumeration descriptions see `act` section in the [enumeration mappings](https://github.com/companieshouse/api-enumerations/blob/master/disqualified_officer_descriptions.yml)"
				},
				"article": {
					"description": "The article of the act under which the disqualification was made.",
					"type": "string",
					"notes": "Only applicable if `reason.act` is `company-directors-disqualification-northern-ireland-order-2002`."
				},
				"section": {
					"description": "The section of the act under which the disqualification was made.",
					"type": "string",
					"notes": "Only applicable if `reason.act` is `company-directors-disqualification-act-1986`."
				}
			},
			"required": [
				"description_identifier",
				"act"
			]
		}
	}
}
