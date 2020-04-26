# helloworld

	/**
	 * 回显表情的内容处理
	 * 
	 * @param content
	 * @return
	 */
	public static String showContent(String content) {
		return EmojiConverterUtil.unicodeStr(content);
	}

	public static void main(String[] args) {

		System.out.println(UUID.randomUUID().toString().replace("-", ""));
	}

	private static String getAge(Map<String, String> map) {

		return MyStringUtil.toString(map.get("age"));
	}
